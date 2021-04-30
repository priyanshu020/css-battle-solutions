# [Target #12 - Wiggly Moustache](https://cssbattle.dev/play/12)

![](https://cssbattle.dev/targets/12.png)

```HTML
<!-- Battle #1 - Pilot Battle/ #12 - Wiggly Moustache -->
<div class="c c1"></div>
<div class="c c2"></div>
<div class="overlay o1"></div>
<div class="overlay o2"></div>
<div class="overlay o3"></div>
<div class="overlay o4"></div>
<style>
  body {
    background: #F5D6B4;
  }
  .c {
    width: 60px;
    height: 30px;
    border: 20px solid #D86F45;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    border-top: none;
    position: absolute;
  }
  .c1 {
    top: 150;
    left: 70;
    -webkit-box-reflect: right 60px;
  }
  .c2 {
    top: 100;
    left: 150;
    transform: rotate(180deg);
  }
  .overlay {
    width: 20px;
    height: 20px;
    background: #D86F45;
    border-radius: 50%;
    position: absolute;
    top: 140;
  }
  .o1 {
    left: 70;
  }
  .o2 {
    left: 310;
  }
  .o3 {
    left: 150;
  }
  .o4 {
    left: 230;
  }
</style>
```
