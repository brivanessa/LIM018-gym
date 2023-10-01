---
difficulty:
  - beginner
OAs:
  - css/box-model
projects:
  - memory-match
  - social-network
---

# CSS Totally Triangle

[https://cssbattle.dev/play/13](https://cssbattle.dev/play/13)

![CSS Totally Triangle](css_totally-triangle.png)

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

> *Hint:* [https://css-tricks.com/snippets/css/css-triangle/](https://css-tricks.com/snippets/css/css-triangle/)

__Solución__
```html
<div></div>
<style>
  *{
    margin:0;
    background: #0B2429
  }
 div {
  width:0px;
  height:0px;
  border-left:8.9rem solid #F3AC3C;
  border-top:0rem solid transparent;
  border-bottom: 8.9rem solid transparent; 
}
</style>
```
