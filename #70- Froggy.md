# [Target #70 - Froggy](https://cssbattle.dev/play/70)

![](https://cssbattle.dev/targets/70.png)

```HTML
<!-- Battle #13 - Clip/ #70 - Froggy -->
<div class="l-i"></div>
<div class="l-inner-i"></div>
<div class="l-p"></div>
<div class="r-i"></div>
<div class="r-inner-i"></div>
<div class="r-p"></div>
<div class="l-nose"></div>
<div class="r-nose"></div>
<div class="head"></div>
<style>
  body {
    background: #293462;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .l-i {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #FE5F55;
    position: absolute;
    top: 85px;
    left: 140px;
  }
  .l-inner-i {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #FFF1C1;
    position: absolute;
    top: 95px;
    left: 150px;
    z-index: 2;
  }
  .l-p {
    width: 10px;
    height: 10px;
    background: #293462;
    z-index: 2;
    border-radius: 50%;
    position: absolute;
    top: 105px;
    left: 160px;
  }
  .r-i {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #FE5F55;
    position: absolute;
    top: 85px;
    left: 210px;
  }
  .r-inner-i {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #FFF1C1;
    position: absolute;
    top: 95px;
    left: 220px;
    z-index: 2;
  }
  .r-p {
    width: 10px;
    height: 10px;
    background: #293462;
    z-index: 2;
    border-radius: 50%;
    position: absolute;
    top: 105px;
    left: 230px;
  }
  .l-nose {
    width: 10px;
    height: 10px;
    background: #293462;
    z-index: 2;
    border-radius: 50%;
    position: absolute;
    top: 160px;
    left: 185px;
  }
  .r-nose {
    width: 10px;
    height: 10px;
    background: #293462;
    z-index: 2;
    border-radius: 50%;
    position: absolute;
    top: 160px;
    left: 205px;
  }
  .mouth {
    background: #A64942;
  }
  .head {
    width: 150px;
    height: 100px;
    background: #A64942;
    position: absolute;
    top: 110px;
    left: 125px;
    border-radius: 90px;
    overflow: hidden;
  }
  .head::before {
    content: '';
    width: 250px;
    height: 200px;
    background: #FE5F55;
    border-radius: 46%;
    position: absolute;
    top: -130px;
    left: -50;
  }
  
</style>
```
