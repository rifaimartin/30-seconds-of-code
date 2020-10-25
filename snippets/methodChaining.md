---
title: methodChaining
tags: array,intermediate,chain
---

Chaining method with high order function.

- Use higher order function, `filter,map,reduce` for process data
- `reduce` is the last function in process and it will return its final value 

```js
const result = numbers.filter(a => a > 5).map(a => a * 3).reduce((acc, cur) => acc + cur);
```

```js
const numbers = [-1, 8, 9, 1, 4, -5, -4, 3, 2, 9];
filter // 8,9,9
map // 24, 27, 27
result  // 78
```
