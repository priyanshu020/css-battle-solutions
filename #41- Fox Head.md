# [Target #41 - Fox Head](https://cssbattle.dev/play/41)

![](https://cssbattle.dev/targets/41.png)

```HTML
<!-- Battle #7 - Backface/ #41 - Fox Head -->
<div class="ear l"></div>
<div class="ear r"></div>
<div class="c"></div>
<div class="o"></div>
<style>
  body {
    background: #293462;
  }
  .c {
    width: 30px;
    height: 30px;
    background: #293462;
    border-radius: 50%;
    position: absolute;
    top: 140;
    left: 165;
    -webkit-box-reflect: right 10px;
  }
  .ear {
    width: 50px;
    height: 135px;
    background: #FE5F55;
    position: absolute;
  }
  .l {
    border-radius: 0 40px 0 0;
    top: 80;
    left: 150;
  }
  .r {
    border-radius: 40px 0 0 0;
    top: 80;
    left: 200;
  }
  .o {
    width: 50px;
    height: 60px;
    background: #293462;
    border-radius: 0 40px 0 0;
    position: absolute;
    top: 180;
    left: 150;
    -webkit-box-reflect: right 0px;
  }
</style>
```
