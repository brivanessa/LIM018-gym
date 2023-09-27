---
difficulty:
  - beginner
OAs:
  - css selectors
  - box model
  - position
projects:
  - data lovers
  - social network
---

# CSS Boxception

[https://cssbattle.dev/play/23](https://cssbattle.dev/play/23)

![CSS Boxception](css_boxception.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
 <div class="generalDiv">
  <div class="greensquare">
    <div class="greenDiv">
       <div class="yellowDiv">
      </div>
    </div>
  </div>
</div>
<style>
  .greensquare {
    width: 50%;
    height: 67%;
    background: #1A4341;
    display:flex;
    align-items:flex-end;
  }
  .yellowDiv{
    background: #F3AC3C;
    width: 50%;
    height: 50%;
  }
  .greenDiv{
    background: #998235;
    width: 50%;
    height: 50%;
    display:flex;
    align-items:flex-end;
    justify-content:flex-end;
  }
  *{
    padding:0%;
    margin:0%;
  }
  .generalDiv{
    background:#F3AC3C;
     width: 100%;
    height: 100%;
       display:flex;
    justify-content:center;
    align-items:center;
  }
</style>
```
