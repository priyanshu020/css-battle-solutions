# [Target #73 - Happy Tiger](https://cssbattle.dev/play/73)

![](https://cssbattle.dev/targets/73.png)

```HTML
<!-- Battle #13 - Clip/ #73 - Happy Tiger -->
<div class="head"></div>
<div class="l-ear"></div>
<div class="inner-l-ear"></div>
<div class="r-ear"></div>
<div class="inner-r-ear"></div>
<div class="eye"></div>
<div class="nose-lc"></div>
<div class="nose-l"></div>
<div class="nose-rc"></div>
<div class="mouth"></div>
<style>
  body {
    background: #F3AC3C;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .head {
    width: 150px;
    height: 150px;
    background: #998235;
    border-radius: 75px 75px 60px 60px;
    z-index: -1;
    overflow: hidden;
    position: relative;
  }
  .head::after {
    content: '';
    width: 30px;
    height: 30px;
    background-color: #1A4341;
    position: absolute;
    top: -11;
    left: 60;
    transform: rotate(45deg);
    z-index: 10;
  }
  .l-ear {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #1A4341;
    position: absolute;
    top: 75px;
    left: 125px;
    z-index: -2;
  }
  .inner-l-ear {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #998235;
    position: absolute;
    top: 65px;
    left: 115px;
    z-index: -3;
  }
  .r-ear {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #1A4341;
    position: absolute;
    top: 75px;
    left: 235px;
    z-index: -2;
  }
  .inner-r-ear {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #998235;
    position: absolute;
    top: 65px;
    left: 225px;
    z-index: -3;
  }
  .eye {
    width: 20px;
    height: 20px;
    background-color: #1A4341;
    border-radius: 50%;
    position: absolute;
    top: 135px;
    left: 150px;
    z-index: 2;
    -webkit-box-reflect: right 60px;
  }
  .nose-lc {
    width: 20px;
    height: 10px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border: 10px solid #1A4341;
    border-top: 0px;
    position: absolute;
    top: 180px;
    left: 165px;
    z-index: 3;
  }
  .nose-l {
    width: 30px;
    height: 10px;
    background-color: #1A4341;
    position: absolute;
    top: 170px;
    z-index: 3;
    transform: rotate(90deg);
  }
  .nose-rc {
    width: 20px;
    height: 10px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border: 10px solid #1A4341;
    border-top: 0px;
    position: absolute;
    top: 180px;
    left: 195px;
    z-index: 3;
  }
  .mouth {
    width: 100px;
    height: 40px;
    background-color: #FFFFFF;
    border-radius: 50px 50px 100px 100px;
    position: absolute;
    top: 170px;
    z-index: 2;
  }
</style
```
