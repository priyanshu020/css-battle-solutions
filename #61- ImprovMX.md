# [Target #61 - ImprovMX](https://cssbattle.dev/play/61)

![](https://cssbattle.dev/targets/61.png)

```HTML
<!-- Battle #12 - Blend/ #61 - ImprovMX -->
<div class="small-rect"></div>
<div class="mid-rect"></div>
<div class="tilt-rect1"></div>
<div class="tilt-rect2"></div>
<div class="mid-line"></div>
<div class="invisible-line"></div>
<div class="line1"></div>
<div class="line2"></div>
<style>
  body {
    background-color: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .small-rect {
    width: 30px;
    height: 20px;
    background: transparent;
    border: 10px solid #5DBCF9;
    position: absolute;
    top: 66px;
  }
  .mid-rect {
    width: 80px;
    height: 50px;
    background: transparent;
    border: 10px solid #5DBCF9;
    border-bottom: none;
    position: absolute;
    top: 96.5px;
  }
  .tilt-rect1 {
    width: 80px;
    height: 21px;
    background: transparent;
    border: 10px solid #5DBCF9;
    border-right: none;
    border-bottom: none;
    position: absolute;
    top: 146px;
    left: 123px;
    transform: rotate(-30deg);
  }
  .tilt-rect2 {
    width: 80px;
    height: 21px;
    background: transparent;
    border: 10px solid #5DBCF9;
    border-left: none;
    border-bottom: none;
    position: absolute;
    top: 146px;
    left: 185px;
    transform: rotate(30deg);
  }
  .mid-line {
    width: 60px;
    border-top: 10px solid #5DBCF9;
    transform: rotate(90deg);
    position: absolute;
    top: 160px;
  }
  .invisible-line {
    width: 150px;
    border-top: 13px solid #191919;
    position: absolute;
    top: 194px;
  }
  .line1 {
    width: 200px;
    border-top: 10px solid #5DBCF9;
    position: absolute;
    top: 204px;
  }
  .line2 {
    width: 110px;
    border-top: 10px solid #5DBCF9;
    position: absolute;
    top: 224px;
  }
</style>
```
