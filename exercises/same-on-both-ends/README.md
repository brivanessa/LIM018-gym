---
difficulty:
  - beginner
OAs:
  - strings
projects:
  - cipher
  - card validation
---

# Same on both ends

[https://edabit.com/challenge/JDDeK9jSFKJbfzhMt](https://edabit.com/challenge/JDDeK9jSFKJbfzhMt)

Dada una oración, retorna el número de palabras cuya primera y última letra sean
**iguales**.

Ejemplos:

```js
countSameEnds("Pop! goes the balloon") // => 1

countSameEnds("And the crowd goes wild!") // => 0

countSameEnds("No I am not in a gang.") // => 1
```

Notas

- No cuentes palabras que tengan un solo caracter (tales como "I" y "a"
  en el ejemplo 3).
- La función no debería ser _case sensitive_, es decir la "P" mayúscula debería
  coincidir con la "p" minúscula.
- Ten ojo con los signos de puntuación u otros caracteres que no sean letras.
- ¡“Puntos” extra si usas expresiones regulares!

__Solución:__
```js
function countSameEnds(str) {
	const strMayus=str.toUpperCase().split("")
	const strFilter=strMayus.filter((item)=>{
		const itemCode=item.codePointAt(0);
		return itemCode===32||(itemCode>=65 && itemCode<=90)
	})
	const strArray=strFilter.join("").split(" ")
	return strArray.map(item=>{
		const wordArray=item.split("");
		const wordLength=wordArray.length;
		return wordLength>1&&(wordArray[0]===wordArray[wordLength-1])
	}).filter(item=>item===true).length
}
```
