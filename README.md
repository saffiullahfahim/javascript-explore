# javascript-explore
JavaScript Explore and learn the programming...


### How to compare two array or object?
We know that when we want to compare two object or array found that it is always flase. But why?
```
let a = {x: 1};
let b = {x: 1};

console.log(a == b); // false

let arr1 = [1, 2];
let arr2 = [1, 2];

console.log(arr1 == arr2) // false

```
#### We can compare two array or object when we convert these array or object to string.
```
let a = {x: 1};
let b = {x: 1};

console.log(JSON.stringify(a) == JSON.stringify(b)); // true

let arr1 = [1, 2];
let arr2 = [1, 2];

console.log(JSON.stringify(arr1) == JSON.stringify(arr2)) // true

```
