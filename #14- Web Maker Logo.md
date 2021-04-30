# [Target #14 - Web Maker Logo](https://cssbattle.dev/play/14)

![](https://cssbattle.dev/targets/14.png)

```HTML
<!-- Battle #2 - Visibility/ #14 - Web Maker Logo -->
<div class="t left"></div>
<div class="t right"></div>
<style>
  body {
    background: #F2F2B6;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .t {
    width: 0;
    border-left: 75px solid transparent;
  	border-right: 75px solid transparent;
    position: absolute;
  }
  .left {
  	border-top: 130px solid #FF6D00;
    left: 60;
  }
  .right {
  	border-bottom: 130px solid #FF6D00;
    right: 60;
  }
  .left::before, .right::before {
    content: '';
    position: absolute;
    border-left: 75px solid transparent;
  	border-right: 75px solid transparent;
  }
  .right::before {
    left: -95;
  	border-bottom: 130px solid #FD4602;;
  }
  .left::before {
    left: -55;
    top: -130;
  	border-top: 130px solid #FD4602;
    z-index: -1;
  }
</style>
```
