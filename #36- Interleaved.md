# [Target #36 - Interleaved](https://cssbattle.dev/play/36)

![](https://cssbattle.dev/targets/36.png)

```HTML
<!-- Battle #7 - Backface/ #36 - Interleaved -->
<div class="b y1"></div>
<div class="b g1"></div>
<div class="b y2"></div>
<div class="b g2"></div>
<div class="b y3"></div>
<style>
  body {
    background: #1A4341;
  }
  .b {
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    position: absolute;
  }
  .y1 {
    left: 25;
    bottom: 0;
  }
  .g1 {
    background: #998235;
    transform: rotate(180deg);
    left: 100;
    top: 0;
  }
  .y2 {
    left: 175;
    bottom: 0;
  }
  .g2 {
    background: #998235;
    transform: rotate(180deg);
    left: 250;
    top: 0;
  }
  .y3 {
    left: 325;
    bottom: 0;
  }
</style>
```
