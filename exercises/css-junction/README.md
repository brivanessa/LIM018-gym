---
difficulty:
  - newbie
OAs:
  - css selectors
  - box model
projects:
  - data lovers
  - social network
---

# CSS Junction

[https://cssbattle.dev/play/84](https://cssbattle.dev/play/84)

![CSS Junction](css-junction.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Solución__

```html
<div class="general">
  <div class="lightDiv">
    <div class="light"></div>
    <div class="lightSec"></div>
  </div>
  <div class="darkDiv">
    <div class="dark"></div>
    <div class="darkSec"></div>
  </div>
</div>
<style>
  *,.general,.lightDiv, .darkDiv{
    margin: 0px;
    padding: 0px;
    height:100%;
    width:100%;
  }
   .general {
     position: relative;
   }
   .lightDiv {
    position: absolute;
    background: #191919;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    display: flex;
  }
  .darkDiv {
    position: absolute;
    background:transparent;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    display: flex;
  }
  
  .light, .lightSec {
    height: 43.5%;
    width:10%;
    background: #FE5F55;
    border-bottom-right-radius:20px;
    border-bottom-left-radius:20px;
  }
  .lightSec{
    transform: scaleY(-1);
  }
   .dark {
    transform: scaleX(-1);
  }
  .dark, .darkSec {
    background:#A64942;
    height: 13.5%;
    width:45%;
    border-top-left-radius:20px;
    border-bottom-left-radius:20px;
  }
</style>
```
