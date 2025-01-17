---
difficulty:
  - intermediate
OAs:
  - Métodos de arrays
  - Manipulación de objetos
projects:
  - data-lovers
  - memory-match
---

# Ask for missing details

[https://www.codewars.com/kata/583d972b8bbc0402cf000121/train/javascript](https://www.codewars.com/kata/583d972b8bbc0402cf000121/train/javascript)

Se le proporcionará un array de objetos que representan datos sobre los
desarrolladores que se han inscrito para asistir a la próxima reunión.

Dado el siguiente array de entrada:

```js
let list1 = [
  { firstName: null, lastName: 'I.', country: 'Argentina', continent: 'Americas', age: 35, language: 'Java' },
  { firstName: 'Lukas', lastName: 'X.', country: 'Croatia', continent: 'Europe', age: 35, language: null },
  { firstName: 'Madison', lastName: 'U.', country: 'United States', continent: 'Americas', age: 32, language: 'Ruby' }
];
```

Escribe una función que:

1. Agregue la propiedad `question` a cada objeto del array de entrada donde el
  desarrollador no ha proporcionado los detalles relevantes (aquellas propiedades
  en las que el valor es `null` ). El valor de la propiedad `question` debe ser el
  siguiente string:

    Hi, could you please provide your `<property name>`.

2. La función debe retornar sólo los desarrolladores con detalles faltantes:

```js
[
  { firstName: null, lastName: 'I.', country: 'Argentina', continent: 'Americas', age: 35, language: 'Java',
  question: 'Hi, could you please provide your firstName.' },
  { firstName: 'Lukas', lastName: 'X.', country: 'Croatia', continent: 'Europe', age: 35, language: null,
  question: 'Hi, could you please provide your language.' }
]
```

__Solución:__

```js
function askForMissingDetails(list) {
  return list.filter((item)=>{
    for (let clave in item){
      if(item[clave]===null){
        item.question=`Hi, could you please provide your ${clave}.`
      }
    }
    return item.question
  })
}
```
