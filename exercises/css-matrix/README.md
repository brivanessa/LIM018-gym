---
difficulty:
  - beginner
OAs:
  - css/box-model
projects:
  - memory-match
  - social-network
---

# CSS Matrix

[https://cssbattle.dev/play/18](https://cssbattle.dev/play/18)

![Matrix](css_matrix.png)

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

> *Hint:* [https://singhak.in/draw-half-and-quarter-circle-with-css/](https://singhak.in/draw-half-and-quarter-circle-with-css/)
>
__Solución:__
```html
<div class="generalDiv">
 <div class="triangle"></div>
 <div class="triangle2"></div>
 <div class="triangle"></div>
 <div class="triangle2"></div>
 <div class="triangle2"></div>
 <div class="triangle"></div>
 <div class="triangle2"></div>
 <div class="triangle"></div>
 <div class="triangle"></div>
 <div class="triangle2"></div>
 <div class="triangle"></div>
 <div class="triangle2"></div>
</div>
<style>
*{
  margin: 0px;
  background: #5C434C
}
.generalDiv{
 width: 100%; 
 height: 100%; 
 display: grid;
 grid-template-columns: 1fr 1fr 1fr 1fr;
 grid-template-rows: 1fr 1fr 1fr;
 justify-items: center;
 align-items: center; 
}
  .triangle, .triangle2 {
   width: 80px; 
   height: 80px;  
   border-radius: 100% 0 0 0;   
  }
  .triangle {
   background: #F09462;
  }
 .triangle2 {
   background: #F5D6B4;
  }
</style>
```
