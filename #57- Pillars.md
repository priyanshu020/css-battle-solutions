# [Target #57 - Pillars](https://cssbattle.dev/play/57)

![](https://cssbattle.dev/targets/57.png)

```HTML
<!-- Battle #11 - Overflow/ #57 - Pillars -->
<div class="box"></div>
<div class="corner c1"></div>
<div class="corner c2"></div>
<div class="yellow y1"></div>
<div class="yellow y2"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .box {
    width: 110px;
    height: 110px;
    background: #4F77FF;
  }
  .corner {
    width: 55px;
    height: 55px;
    background: #191919;
    border-radius: 50%;
    position: absolute;
    top: 80;
  }
  .c1 {
    left: 130;
    -webkit-box-reflect: below 30px;
  }
  .c2 {
    left: 215;
    -webkit-box-reflect: below 30px;
  }
  .yellow {
    width: 45px;
    height: 45px;
    background: #F9E492;
    border-radius: 50%;
    position: absolute;
    top: 75;
  }
  .y1 {
    left: 125;
	-webkit-box-reflect: below 60px;
  }
  .y1::after {
    content: '';
    width: 30px;
    height: 30px;
    background: #4F77FF;
    border-radius: 50%;
    position: absolute;
  }
  .y2 {
    left: 230;
	-webkit-box-reflect: below 60px;
  }
  .y2::after {
    content: '';
    width: 30px;
    height: 30px;
    background: #4F77FF;
    border-radius: 50%;
    position: absolute;
    left: 15;
  }
</style>
```
