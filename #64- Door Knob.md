# [Target #64 - Door Knob](https://cssbattle.dev/play/64)

![](https://cssbattle.dev/targets/64.png)

```HTML
<!-- Battle #12 - Blend/ #64 - Door Knob -->
<div class="circle"></div>
<div class="dot"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 100px;
    height: 100px;
    background: #E08027;
    border-radius: 50%;
    border: 30px solid #824B20;
  }
  .circle::after {
    content: '';
    width: 80px;
    height: 40px;
    background: #E08027;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    border: 20px solid #FFF58F;
    border-top: 0;
    position: absolute;
    top: 150;
    left: 140;
  }
  .dot {
    width: 20px;
    height: 20px;
    background: #FFF58F;
    border-radius: 50%;
    position: absolute;
    top: 140;
    left: 140;
	-webkit-box-reflect: right 80px;
  }
</style>
```
