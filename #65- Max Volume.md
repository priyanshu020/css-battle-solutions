# [Target #65 - Max Volume](https://cssbattle.dev/play/65)

![](https://cssbattle.dev/targets/65.png)

```HTML
<!-- Battle #12 - Blend/ #65 - Max Volume -->
<div class="speaker"></div>
<div class="w w3"></div>
<div class="w w2"></div>
<div class="w w1"></div>
<style>
  body {
    background: #191919;
  }
  .speaker {
    width: 0;
    border: 100px solid transparent;
    border-right: 100px solid #5DBCF9;
    position: absolute;
    top: 50;
    left: 0;
  }
  .speaker::before {
    content: '';
    width: 50px;
    height: 50px;
    background: #5DBCF9;
    border-radius: 10px 0 0 10px;
    position: absolute;
    top: -25;
    left: -25;
  }
  .w {
    background: #191919;
    border: 10px solid #5DBCF9;
    border-bottom: none;
    transform: rotate(90deg);
    position: absolute;
  }
  .w3 {
    width: 180px;
    height: 90px;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
    top: 100;
    left: 175;
  }
  .w2 {
    width: 130px;
    height: 65px;
    border-top-left-radius: 75px;
    border-top-right-radius: 75px;
    top: 112;
    left: 187;
  }
  .w1 {
    width: 80px;
    height: 40px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    top: 125;
    left: 200;
  }
</style>
```
