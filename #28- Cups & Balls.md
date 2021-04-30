# [Target #28 - Cups & Balls](https://cssbattle.dev/play/28)

![](https://cssbattle.dev/targets/28.png)

```HTML
<!-- Battle #4 - Display/ #28 - Cups & Balls -->
<div class="c c1"></div>
<div class="c c2"></div>
<div class="c c3"></div>
<div class="c c4"></div>
<div class="b b1"></div>
<div class="b b2"></div>
<div class="b b3"></div>
<div class="b b4"></div>
<style>
  body {
    background: #1A4341;
  }
  .c {
    width: 50px;
    height: 50px;
    background: #998235;
    border-radius: 50%;
    position: absolute;
  }
  .c1 {
    top: 90;
    left: 70;
  }
  .c2 {
    top: 160;
    left: 140;
  }
  .c3 {
    background: #F3AC3C;
    top: 160;
    left: 210;
  }
  .c4 {
    background: #F3AC3C;
    top: 90;
    left: 280;
  }
  .b {
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    border-radius: 0 0 50% 50%;
    position: absolute;
  }
  .b1 {
    top: 160;
    left: 70;
  }
  .b2 {
    transform: rotate(180deg);
    top: 90;
    left: 140;
  }
  .b3 {
    background: #998235;
    transform: rotate(180deg);
    top: 90;
    left: 210;
  }
  .b4 {
    background: #998235;
    top: 160;
    left: 280;
  }
</style>
```
