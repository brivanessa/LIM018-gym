---
difficulty:
  - newbie
OAs:
  - css selectors
  - box layout
projects:
  - data lovers
  - social network
---

# CSS Carrom

[https://cssbattle.dev/play/2](https://cssbattle.dev/play/2)

![CSS Carrom](css-carrom.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
<div class="generalDiv">
  <div class="subDiv"></div>
  <div class="subDiv"></div>
</div>
<div class="generalDiv">
  <div class="subDiv"></div>
  <div class="subDiv"></div>
</div>
<style>
  .generalDiv{
    gap:25%;
    display: flex;
    width: 100%;
    height: 50%;
    flex-direction:row;
    justify-content:space-around;
    align-items:center;
    background:#62374E;
  }
 .subDiv{
    width: 13%;
    height: 33%;
    background: #FDC57B;
  }
  *{
    padding:0px;
    margin:0px;
  }
</style>

```
