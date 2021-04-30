# [Target #66 - Batmicky](https://cssbattle.dev/play/66)

![](https://cssbattle.dev/targets/66.png)

```HTML
<!-- Battle #12 - Blend/ #66 - Batmicky -->
<div class="body"></div>
<div class="w1"></div>
<div class="w2"></div>
<div class="ear"></div>
<div class="head"></div>
<style>
  body {
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .body {
    width: 245px;
    height: 80px;
    background: #F2AD43;
    position: absolute;
    top: 100;
  }
  .body::before {
    content: '';
    width: 80px;
    height: 30px;
    background: #191919;
    border-radius: 0 0 10px 10px;
    position: absolute;
    top: 0;
    left: 83;
    z-index: 10;
  }
  .w1 {
    width: 100px;
    height: 100px;
    background: #191919;
    border-radius: 50%;
    position: absolute;
    left: 25;
    -webkit-box-reflect: right 150px;
  }
  .w2 {
    width: 130px;
    height: 100px;
    background: #191919;
    border-radius: 50%;
    position: absolute;
    top: 160;
    left: 85;
    -webkit-box-reflect: right -25px;
    z-index: 11;
  }
  .ear {
    width: 10px;
    height: 10px;
    background: #F2AD43;
    border-radius: 50%;
    position: absolute;
    top: 105;
    left: 185;
    z-index: 10;
    -webkit-box-reflect: right 10px;
  }
  .head {
    width: 20px;
    height: 75px;
    background: #F2AD43;
    position: absolute;
    top: 110;
    left: 190;
    z-index: 10;
  }
</style>
```
