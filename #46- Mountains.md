# [Target #46 - Mountains](https://cssbattle.dev/play/46)

![](https://cssbattle.dev/targets/46.png)

```HTML
<!-- Battle #9 - Margin/ #46 - Mountains -->
<div class="circle"></div>
<style>
  body {
    background: #293462;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle {
    width: 200px;
    height: 200px;
    background: #FFF1C1;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
  }
  .circle::after {
    content: '';
    width: 30px;
    height: 50px;
    background: #FE5F55;
    position: absolute;
    top: 132;
    left: 20;
    transform: rotate(140deg);
    overflow: hidden;
  }
  .circle::before {
    content: '';
    width: 170px;
    height: 150px;
    background: #FE5F55;
    position: absolute;
    top: 100;
    left: 50;
    transform: rotate(133deg);
    overflow: hidden;
  }
</style>
```
