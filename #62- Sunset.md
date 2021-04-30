# [Target #62 - Sunset](https://cssbattle.dev/play/62)

![](https://cssbattle.dev/targets/62.png)

```HTML
<!-- Battle #12 - Blend/ #62 - Sunset -->
<div class="box">
  <div class="circle"></div>
  <div class="c1"></div>
  <div class="c2"></div>
</div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .box {
    width: 150px;
    height: 200px;
    background: #F2AD43;
    border-top-left-radius: 72px;
    border-top-right-radius: 72px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    position: relative;
    z-index: 1;
    overflow: hidden;
  }
  .circle {
    height: 60px;
    width: 60px;
    background: #FFF58F;
    position: absolute;
    top: 90px;
    left: 45px;
    clip-path: circle();
    z-index: 500;
    position: relative;
  }
  .c1 {
    height: 200px;
    width: 200px;
    background: #E08027;
    position: absolute;
    top: 100px;
    left: -100px;
    clip-path: circle();
    z-index: 1000;
  }
  .c2 {
    height: 200px;
    width: 200px;
    background: #824B20;
    position: absolute;
    top: 100px;
    left: 50px;
    clip-path: circle();
    z-index: 1000;
  }
</style>
```
