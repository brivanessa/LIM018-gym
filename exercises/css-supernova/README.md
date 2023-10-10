---
difficulty:
  - Intermediate
OAs:
  - css selectors
  - box model
  - position
projects:
  - data lovers
  - social network
---

# CSS Supernova

[https://cssbattle.dev/play/83](https://cssbattle.dev/play/83)

![CSS Boxception](css_supernova.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
<div class=universal>
  <div class=general>
    <div class="subgeneral1">
      <div class="blue"></div>
      <div class="blue1"></div>
    </div>
    <div class="subgeneral2">
      <div class="blue2"></div>
      <div class="blue3"></div>
    </div> 
  </div>
  <div class=yellow></div>
</div>
<style>
  * {
    margin: 0%;
  }
  .universal {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
  }
  .general {
    width: 100%;
    height: 100%;
    background: #243D83;
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: center;
    align-items: center;

  }
  .subgeneral1, .subgeneral2 {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: end;
    justify-content: center;
    gap: 70px;
 
  }
   .subgeneral2 {
    align-items: start;
  }
  
   .blue, .blue1, .blue2, .blue3 {
   width: 50px;
   height: 100px;
   border-radius: 200px 0 0 200px;
   background: #6592CF;
   transform: rotate(45deg)  
  }
  .blue1 {
   transform: rotate(135deg)  
  }
  .blue2 {
   transform: rotate(315deg)  
  }
  .blue3 {
   transform: rotate(225deg)  
  }
   .yellow{
     position:absolute;
     width: 60px;
     height: 60px;
     border-radius: 100%;
     background: #EEB850;
   }
</style>
```
