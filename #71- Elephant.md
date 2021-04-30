# [Target #71 - Elephant](https://cssbattle.dev/play/71)

![](https://cssbattle.dev/targets/71.png)

```HTML
<!-- Battle #13 - Clip/ #71 - Elephant -->
<div class="l-ear"></div>
<div class="head"></div>
<div class="r-ear"></div>
<div class="l-i"></div>
<div class="r-i"></div>
<div class="teeth"></div>
<div class="nose"></div>
                      
<style>
  body {
    background: #998235;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .l-ear {
    width: 80px;
    height: 180px;
    background: #1A4341;
    border-radius: 50%;
    position: absolute;
    top: 60;
    left: 50;
    overflow: hidden;
  }
  .l-ear::after {
    content: '';
    width: 60px;
    height: 175px;
    background: #0B2429;
    border-radius: 50%;
    position: absolute;
    top: 3;
    left: 18;
  }
  .head {
    width: 180px;
    height: 180px;
    background: #1A4341;
    border-radius: 50%;
    z-index: 3;
  }
  .r-ear {
    width: 80px;
    height: 180px;
    background: #1A4341;
    border-radius: 50%;
    position: absolute;
    top: 60;
    left: 270;
    overflow: hidden;
  }
  .r-ear::after {
    content: '';
    width: 60px;
    height: 180px;
    background: #0B2429;
    border-radius: 50%;
    position: absolute;
    top: 0;
    left: 2;
  }
  .l-i {
    width: 20px;
    height: 10px;
    background: #0B2429;
    border: 10px solid #998235;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border-top: none;
    position: absolute;
    top: 150;
    left: 150;
    z-index: 4;
  }
  .r-i {
    width: 20px;
    height: 10px;
    background: #0B2429;
    border: 10px solid #998235;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border-top: none;
    position: absolute;
    top: 150;
    left: 210;
    z-index: 4;
  }
  .teeth {
    width: 80px;
    height: 40px;
    background: transparent;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    border: 20px solid #ffffff;
    border-bottom: none;
    position: absolute;
    top: 190;
    z-index: 4;
  }
  .nose {
    width: 40px;
    height: 120px;
    background: #0B2429;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    position: absolute;
    top: 180;
    z-index: 5;
  }
</style>
```
