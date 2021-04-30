# [Target #59 - Earth](https://cssbattle.dev/play/59)

![](https://cssbattle.dev/targets/59.png)

```HTML
<!-- Battle #11 - Overflow/ #59 - Earth -->
<div class="circle"></div>
<div class="l vl"></div>
<div class="l hl"></div>
<div class="l"></div>
<div class="c c1"></div>
<div class="c c2"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 150px;
    height: 150px;
    background: #4F77FF;
    border-radius: 50%;
  }
  .l {
    width: 150px;
    height: 10px;
    background: #191919;
    position: absolute;
  }
  .vl {
    transform: rotate(90deg);
  }
  .hl {
    top: 105;
    -webkit-box-reflect: below 70px;
  }
  .c {
    width: 150px;
    height: 170px;
    background: transparent;
    border: 10px solid #191919;
    border-radius: 50%;
    position: absolute;
  }
  .c1 {
    left: 155;
  }
  .c2 {
    right: 155;
  }
</style>
```
