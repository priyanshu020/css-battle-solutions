# [Target #29 - Suffocate](https://cssbattle.dev/play/29)

![](https://cssbattle.dev/targets/29.png)

```HTML
<!-- Battle #5 - Inline/ #29 - Suffocate -->
<div class="c c1"></div>
<div class="c c2"></div>
<div class="c c3"></div>
<div class="c c4"></div>
<div class="overlay"></div>
<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .c {
    width: 200px;
    height: 200px;
    background: #F3AC3C;
    border-radius: 50%;
    position: absolute;
  }
  .c1 {
    top: -50;
    left: 0;
  }
  .c2 {
    top: -50;
    right: 0
  }
  .c3 {
    top: 150;
    left: 0;
  }
  .c4 {
    top: 150;
    right: 0;
  }
  .overlay {
    width: 200px;
    height: 200px;
    background: transparent;
    border-left: 100px solid #F3AC3C;
    border-right: 100px solid #F3AC3C;
    border-top: 50px solid #F3AC3C;
    border-bottom: 50px solid #F3AC3C;
  }
</style>
```
