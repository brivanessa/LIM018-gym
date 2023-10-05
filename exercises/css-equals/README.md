---
difficulty:
  - beginner
OAs:
  - css/boxmodel
---

# CSS Equals

[https://cssbattle.dev/play/31](https://cssbattle.dev/play/31)

![CSS Equals](css-equals.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
    <div></div>
    <style>
      div {
        width: 100px;
        height: 100px;
        background: #dd6b4d;
      }
    </style>
```
__Solución__
```html
<div class="generalDiv">
    <div class="yellow"></div>
    <div class="orange"></div>
</div>
<style>
 *{
  background: #AA445F
  }
 .generalDiv {
   height: 100%;
   display: flex;
   justify-content: center;
   align-items: center;
   gap: 50px;
  }
 .yellow, .orange {
   width: 100px;
   height: 200px;
  }
 .yellow {
   border-radius: 200px 0 0 200px;
   background: #F7EC7D
  }
 .orange {
   border-radius: 0 200px 200px 0;
   background: #E38F66
  }
</style>
```
