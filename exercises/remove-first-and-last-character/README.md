---
difficulty:
  - beginner
OAs:
  - strings
  - arrays
projects:
  - cipher
  - card validation
---

# Remove First and Last Character

[https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0/train/javascript](https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0/train/javascript)

El objetivo es crear una función que elimine el primer y último carácter del string.
La función tiene como parámetro un string 'str'. No tienes que preocuparte por
cadenas con menos de dos caracteres.

__Ejemplos__

```js
removeChar('eloquent') ➞ 'loquen';
removeChar('country') ➞ 'ountr';
```
__Solución__
```js
function removeChar(str){
  const strArray = str.split("")
  strArray.shift()
  strArray.pop()
  return strArray.join("")
};
```
