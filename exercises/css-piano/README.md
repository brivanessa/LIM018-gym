---
difficulty:
  - intermediate
OAs:
  - css selectors
  - box model
projects:
  - data lovers
  - social network
---

# CSS Piano

[https://cssbattle.dev/play/80](https://cssbattle.dev/play/80)

![CSS Piano](css-piano.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
<div class="generalDiv">
  <div class="pianoDiv">
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="piano"></div>
    <div class="blackDiv">
      <div class="blackFirst">
        <div class="black"></div>
        <div class="black"></div>
      </div>
      <div class="blackSecond">
        <div class="black"></div>
        <div class="black"></div>
        <div class="black"></div>
      </div> 
    </div>
  </div>
</div>
<style>
  * {
    padding: 0px;
    margin: 0px;
    background:#998235;
  }
  .generalDiv {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items:center;
  }
  .pianoDiv{
    position:relative;
    width: 44%;
    padding: 5px 2px;
    height: 30%;
    background:#191919;
    border-radius: 10px;
    display: flex;
    justify-content:space-around;
    align-items:flex-end;
  }
  .piano{
    width: 11%;
    height: 77%;
    border-radius:4.5px;
    background:#FFFFFF;
  }
  .blackDiv{
    position: absolute;
    display:flex;
    background:transparent;
    width: 100%;
    height: 100%;
  }
  .blackFirst, .blackSecond{
    background:transparent;
    width: 44.8%;
    height: 65%;
    display: flex;
    justify-content:center;
    align-items:flex-end;
    gap: 10px;
  }
   .blackSecond{
    background:transparent;
    width: 52%;
    height: 65%;
  }
   .black{
     width: 15px;
    height: 70%;
    background:#191919;
   }
```
