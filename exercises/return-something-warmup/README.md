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

# Mutual Recursion

## Return Something to Me! {:suspect: Warm-up}

[https://edabit.com/challenge/MvZK536X7fyrWH8Qc](https://edabit.com/challenge/MvZK536X7fyrWH8Qc)

Comencemos!
En este ejercicio deberás crear una función que retorne el string "something" unido
con un espacio " " y el argumento dado a.

__Ejemplos__

```js
giveMeSomething("is better than nothing") ➞ "something is better than nothing"

giveMeSomething("Bob Jane") ➞ "something Bob Jane"

giveMeSomething("something") ➞ "something something"
```
__Solución__
```js
function giveMeSomething(a) {
	return `something ${a}`
}
```

## Objetivos de aprendizaje (OAs)

- Manipulación de strings
