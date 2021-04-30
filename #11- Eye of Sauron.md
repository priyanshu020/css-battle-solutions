# [Target #11 - Eye of Sauron](https://cssbattle.dev/play/11)

![](https://cssbattle.dev/targets/11.png)

```HTML
<!-- Battle #1 - Pilot Battle/ #11 - Eye of Sauron -->
<div class="center"></div>
<div class="c l"></div>
<div class="c r"></div>
<style>
  body {
    background: #191210;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .center {
    width: 100px;
    height: 100px;
    background: #191210;
    border: 20px solid #ECA03D;
    border-radius: 50%;
  }
  .center::after {
    content: '';
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius: 50%;
    position: absolute;
    transform: translate(50%, 50%);
  }
  .c {
    width: 60px;
    height: 30px;
    border: 20px solid #ECA03D;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    border-top: none;
    position: absolute;
  }
  .l {
    top: 150;
    left: 50;
  }
  .r {
    transform: rotate(180deg);
    top: 100;
    left: 250;
  }
</style>
```
