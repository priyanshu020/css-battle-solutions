# [Target #42 - Baby](https://cssbattle.dev/play/42)

![](https://cssbattle.dev/targets/42.png)

```HTML
<!-- Battle #8 - Transition/ #42 - Baby -->
<div class="head"></div>
<div class="i1"></div>
<div class="i2"></div>
<div class="mouth"></div>
<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .head {
    width: 200px;
    height: 200px;
    background: #FE5F55;
    border-radius: 50% 50% 50px 50px;
    position: relative;
    overflow: hidden;
  }
  .head::before {
    content: '';
    width: 100px;
    height: 100px;
    background: #FFF1C1;
    border-radius: 50%;
    position: absolute;
    top: -50;
    left: 5;
  }
  .head::after {
    content: '';
    width: 100px;
    height: 100px;
    background: #FFF1C1;
    border-radius: 50%;
    position: absolute;
    top: -50;
    left: 105;
  }
  .i1 {
    width: 60px;
    height: 60px;
    background: #FFF1C1;
    border-radius: 50%;
    position: absolute;
    top: 140;
    left: 120;
  }
  .i2 {
    width: 60px;
    height: 60px;
    background: #FFF1C1;
    border-radius: 50%;
    position: absolute;
    top: 140;
    left: 220;
  }
  .mouth {
    width: 40px;
    height: 10px;
    background: #FFF1C1;
    position: absolute;
    top: 220;
    border-radius: 10px;
  }
</style>
```
