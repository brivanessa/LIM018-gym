---
difficulty:
  - newbie
OAs:
  - Arreglos
projects:
  - cipher
  - card validation
---

# firstLast6

[https://the-winter.github.io/codingjs/exercise.html?name=firstLast6&title=Array-1](https://the-winter.github.io/codingjs/exercise.html?name=firstLast6&title=Array-1)

Implementa la función firstLast6 que recibe un arreglo con números y
retorne true si el número 6 es el primer o el último elemento
del arreglo. El arreglo tendrá 1 o más elementos.

__Ejemplo:__

```js
    firstLast6([1, 2, 6]) → true
    firstLast6([6, 1, 2, 3]) → true
    firstLast6([13, 6, 1, 2, 3]) → false
```

__Solución:__
```js
function firstLast6(nums){
  let lastNums= nums.length - 1
  return nums[0]===6 ||nums[lastNums]===6
}
```
