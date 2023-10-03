---
difficulty:
  - intermediate
OAs:
  - css/box-model
projects:
  - memory-match
  - social-network
---

# CSS Pokebola

[https://cssbattle.dev/play/95](https://cssbattle.dev/play/95)

![Pokebola](css_pokeball.png)

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

__Solución__
```html
<div class="generalDiv">
  <div>
    <div class="red"></div>
    <div class="white"></div>
  </div>
  <div class="green"></div> 
  <div class="brown"></div> 
  <div class="brownCircle"></div> 
  <div class="yellow"></div> 
</div>
<style>
*{
  background:#6CB3A9
}
.generalDiv{
 width: 100%;
 height: 100%;
 display: flex;
 align-items: center;
 justify-content:center;
 flex-direction:column
}
.red, .white {
 width: 200px;
 height: 100px;
}
.red {
 border-radius:200px 200px 0px 0px;
 background: #D25B70
}
.white {
 border-radius: 0px 0px 250px 250px;
 background: #FFFFFF;
}
.brown,.green {
 position:absolute;
 height: 20px;
}
.brown {
 width: 180px;
 background: #781728;
}
.green {
 width: 200px;
 background: #6CB3A9;
}  
.brownCircle, .yellow {
  position:absolute;
  border-radius: 100%;
}  
.yellow {
  width: 50px;
  height: 50px;
  background: #F6DF96;
} 
.brownCircle {
  width: 70px;
  height: 70px;
  background: #781728;
}    
</style>
```
