---
difficulty:
  - beginner
OAs:
  - strings
  - arrays
projects:
  - data lovers
  - cipher
  - card validation
---

# Abbreviate a Two Word Name

[https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/train/javascript](https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/train/javascript)

Escribe una función que convierte un nombre en iniciales. Esta función toma
exactamente dos palabras con un espacio entre ellos.

La salida debe ser dos letras capitalizadas con un punto que las separa.

__Ejemplo 1__

- Entrada: `Sam Harris`
- Salida: `S.H`

__Ejemplo 2__

- Entrada: `Patrick Feeney`
- Salida: `P.F`
  
__Solución__
```js
function abbrevName(name){
 return (name.split(" ").map(item=>(item.charAt(0)))).join(".").toUpperCase()
}
```
