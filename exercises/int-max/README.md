---
difficulty:
  - newbie
OAs:
  - conditionals
  - functions
projects:
  - cipher
  - card validation
---

# intMax

[https://the-winter.github.io/codingjs/exercise.html?name=intMax&title=Warmup-1](https://the-winter.github.io/codingjs/exercise.html?name=intMax&title=Warmup-1)

Completa la función `intMax` que recibe tres valores tipo
int, a b c y retorna el mayor.

__Ejemplo__

```js
    intMax(1, 2, 3) → 3
    intMax(1, 3, 2) → 3
    intMax(3, 2, 1) → 3
```
__Solución__

```js
function intMax(a, b, c){
  return (a>b)&(a>c)?a:((b>a)&(b>c)?b:c)
}
```
