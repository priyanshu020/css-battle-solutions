# [Target #72 - Sheep](https://cssbattle.dev/play/72)

![](https://cssbattle.dev/targets/72.png)

```HTML
<!-- Battle #13 - Clip/ #72 - Sheep -->
<div class="o o1"></div>
<div class="o o2"></div>
<div class="o o3"></div>
<div class="o o4"></div>
<div class="o o5"></div>
<div class="o o6"></div>
<div class="o o7"></div>
<div class="o o8"></div>
<div class="face"></div>
<div class="eye"></div>
<style>
  body {
    background: #243D83;
  }
  .o {
    width: 60px;
    height: 50px;
    background: #6592CF;
    border-radius: 50%;
    position: absolute;
  }
  .o1 {
    top: 65;
    left: 170;
  }
  .o2 {
    transform: rotate(45deg);
    top: 85;
    left: 210;
  }
  .o3 {
    transform: rotate(90deg);
    top: 125;
    left: 230;
  }
  .o4 {
    transform: rotate(135deg);
    top: 165;
    left: 210;
  }
  .o5 {
    top: 185;
    left: 170;
  }
  .o6 {
    transform: rotate(-45deg);
    top: 85;
    left: 130;
  }
  .o7 {
    transform: rotate(-90deg);
    top: 125;
    left: 110;
  }
  .o8 {
    transform: rotate(-135deg);
    top: 165;
    left: 130;
  }
  .face {
    width: 80px;
    height: 70px;
    background: #6592CF;
    position: absolute;
    top: 135;
    left: 160;
  }
  .face::after {
    content: '';
    width: 60px;
    height: 40px;
    background: #243D83;
    border-radius: 0;
    border-bottom-left-radius: 100px;
    border-bottom-right-radius: 100px;
    position: absolute;
    left: 10;
  }
  .eye {
    width: 10px;
    height: 10px;
    background: #6592CF;
    border-radius: 50%;
    position: absolute;
    top: 130;
    left: 185;
	-webkit-box-reflect: right 10px;
  }
</style>
```
