---
difficulty:
  - intermediate
OAs:
  - css selectors
  - box model
  - border-radius
  - position
projects:
  - data lovers
  - social network
---

# CSS Sunset

[https://cssbattle.dev/play/91](https://cssbattle.dev/play/91)

![CSS Sunset](css_sunset.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
 <div class="generalDiv">
  <div class="roundDiv">
  </div>
</div>
<div class="generalSecondDiv">
  <div class="roundSecondDiv">
     <div class="greenRound"></div>
     <div class="greenRound"></div>
     <div class="greenRound"></div>
     <div class="greenRound"></div>

  </div>
</div>
<style>
  .roundDiv, .roundSecondDiv {
    width: 50%;
    height: 67%;
    background: #f6df96;
  }
  .roundDiv {
   border-radius: 100px 100px 0 0;
  }
  
  .roundSecondDiv {
   background:#f6df96;
   border-radius: 0px 0px 100px 100px;
    display:flex;
    flex-direction:column;
    gap: 9.9%;
  }
  
  .generalDiv, .generalSecondDiv{
    width: 100%;
    height: 50%;
    background: #6CB3A9;
    display: flex;
    justify-content: center;    
  }
  .generalDiv{
    align-items: flex-end;
    background: #D25B70;
  }
  .greenRound{
    width: 100%;
    height: 15.2%;
    background: #6CB3A9;
  }
  *{
    margin:0px;
  }
</style>
```
