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

# CSS Ripples

[https://cssbattle.dev/play/94](https://cssbattle.dev/play/94)

![CSS Ripples](css-ripples.png)

__Objetivo__

Escriba el HTML/CSS en el editor para replicar la imagen objetivo de la derecha.

__Código de base__

```html
<div class="generalDiv">
  <div class="circle yellow">
    <div class="circle green">
      <div class="circle yellow2">
        <div class="circle green2">
          <div class="circle middle">
            <div class="circle green3">
              <div class="circle yellow3">
               <div class="circle green4">
                <div class="circle yellow4">
                
                </div>
              </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
<style>
  * {
    margin:0px;
    background:#0E2E2C;
  }
  .generalDiv{
    width: 100%;
    height: 100%;
    display:flex;
    align-items:center;
    justify-content:center;
  }
  .circle{
    border-radius: 100%;
    display:flex;
    align-items:center;
    justify-content:center;
  }
.yellow,.yellow2,.yellow3,.yellow4{
    background: #F3AC3C;
  }
.green,.green2,.green3,.green4{
    background: #0E2E2C;
  }
  .yellow {
    width: 50%;
    height: 66.5%;
  }
  .green{
    width: 94%;
    height: 94%;
  }
   .yellow2,.green3{
    width: 85%;
    height: 85%;
  }
   .green2{
    width: 90%;
    height: 90%;
  }
  .middle{
    width: 83%;
    height: 83%;
    background: #998235;
  }
   .yellow3 {
    width: 80%;
    height: 80%;
  }
  .green4, .yellow4{
    width: 70%;
    height: 70%;
  }
</style>

```
