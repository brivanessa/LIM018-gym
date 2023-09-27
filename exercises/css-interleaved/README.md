---
difficulty:
  - beginner
OAs:
  - css selectors
  - box model
  - border-radius
projects:
  - data lovers
  - social network
---

# CSS Interleaved

[https://cssbattle.dev/play/36](https://cssbattle.dev/play/36)

![CSS Interleaved](css_interleaved.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
  <div class="generalDiv">
  <div class="containerYellow">
    <div class="yellowDiv">
    </div>
  </div>
  <div class="containerGreen">
    <div class="greenDiv">
    </div>
  </div>
    <div class="containerYellow">
    <div class="yellowDiv">
    </div>
  </div>
  <div class="containerGreen">
    <div class="greenDiv">
    </div>
  </div>
    <div class="containerYellow">
    <div class="yellowDiv">
    </div>
  </div>

 </div> 
<style>
  *{
    margin: 0px;
  }
  .containerYellow, .containerGreen {
    width: 19%;
    height: 100%;
    background: #1A4341;
    display: flex;
    justify-content: center;
  }
   .containerYellow{
    align-items:flex-end
  }
  .containerGreen {
    align-items:flex-start
  }
  .yellowDiv{
    width: 65%;
    height: 66.5%;
    background: #F3AC3C;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
  }
  .generalDiv{
    width: 100%;
    height: 100%;
    display:flex;
    justify-content:center;
    background: #1A4341;
  }
    .greenDiv{
    width: 65%;
    height: 66.5%;
    background: #998235;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
  }
</style>
```
