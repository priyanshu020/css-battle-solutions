# [Target #75 - Hippo](https://cssbattle.dev/play/75)

![](https://cssbattle.dev/targets/75.png)

```HTML
<!-- Battle #13 - Clip/ #75 - Hippo -->
<div class="ear"></div>
<div class="head"></div>
<div class="i"></div>
<div class="mouth"></div>
<div class="nose"></div>
<style>
  body {
    background: #191919;
  }
  .ear {
    width: 10px;
    height: 20px;
    background: #000000;
    transform: rotate(-45deg);
    border: 5px solid #FE5F55;
    border-radius: 50%;
    position: absolute;
    top: 70;
    left: 150;
  }
  .ear::after {
    content: '';
    width: 10px;
    height: 20px;
    background: #000000;
    transform: rotate(-90deg);
    border: 5px solid #FE5F55;
    border-radius: 50%;
    position: absolute;
    top: 50;
    left: 50;
  }
  .head {
    width: 130px;
    height: 150px;
    background: #FE5F55;
    border-radius: 60px;
    position: absolute;
    top: 75;
    left: 135;
  }
  .i {
    width: 10px;
    height: 10px;
    background: #000000;
    border-radius: 50%;
    position: absolute;
    top: 125;
    left: 160;
    -webkit-box-reflect: right 60px;
  }
  .mouth {
    width: 150px;
    height: 100px;
    background: #A64942;
    border-radius: 90px 90px 65px 65px;
    position: absolute;
    top: 145;
    left: 125;
  }
  .nose {
    width: 20px;
    height: 30px;
    background: #000000;
    border-radius: 50%;
    transform: rotate(45deg);
    position: absolute;
    top: 165;
    left: 150;
  }
  .nose::after {
    content: '';
    width: 20px;
    height: 30px;
    background: #000000;
    border-radius: 50%;
    transform: rotate(90deg);
    position: absolute;
    top: -55;
    left: 57;
    z-index: 10;
  }
</style>
```
