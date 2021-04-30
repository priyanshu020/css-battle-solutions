# [Target #68 - Bell](https://cssbattle.dev/play/68)

![](https://cssbattle.dev/targets/68.png)

```HTML
<!-- Battle #12 - Blend/ #68 - Bell -->
<div></div>
<div class="c1 circle"></div>
<div class="c2 circle"></div>
<style>
  body{
    position: relative;
    background: #191919
  }
  div{
    width: 120px;
    height: 120px;
    background: #dd6b4d;
    position: absolute;
    top:82px;
    left: 131px;
    background: #E08027;
    z-index: 20;
    border-radius: 60px 60px 10px 10px;
  }
  .circle{
    position: absolute;
    width: 50px;
    height: 50px;
    clip-path: circle();
    z-index: 1;
  }
  .c1{
    background: #F2AD43;
    top: 58px;
    left: 166px;
  }
  .c2{
    background: #824B20;
    top: 177px;
    left: 166px;
  }
</style>
```
