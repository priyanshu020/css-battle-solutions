# [Target #60 - Evil Triangles](https://cssbattle.dev/play/60)

![](https://cssbattle.dev/targets/60.png)

```HTML
<!-- Battle #11 - Overflow/ #60 - Evil Triangles -->
<div class="t tri-1"></div>
<div class="t tri-2"></div>
<div class="box"></div>
<div class="t tri-3"></div>
<style>
  body {
    background: #191919;
  }
  .t {
    width: 0;
    border: 50px solid transparent;
    -webkit-box-reflect: right;
    position: absolute;
    left: 100;
  }
  .tri-1 {
    border-top: 50px solid #4F77FF;
    top: 75;
  }
  .tri-2 {
    border-top: 50px solid #191919;
    top: 125;
    z-index: 10;
  }
  .box {
    width: 200px;
    height: 100px;
    background: #4F77FF;
    position: absolute;
    top: 125;
    left: 100;
  }
  .tri-3 {
    transform: rotate(180deg);
    border-top: 50px solid #191919;
    top: 125;
    left: 150;
  }
  .tri-3::after {
    content: '';
    width: 0;
    border: 50px solid transparent;
    border-top: 50px solid #191919;
    position: absolute;
    top: -50;
    left: 150;
  }
</style>
```
