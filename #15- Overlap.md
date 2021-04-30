# [Target #15 - Overlap](https://cssbattle.dev/play/15)

![](https://cssbattle.dev/targets/15.png)

```HTML
<!-- Battle #2 - Visibility/ #15 - Overlap -->
<div class="c lc"></div>
<div class="c rc">
  <div class="c inner"></div>
</div>
<style>
  body {
    background: #09042A;
  }
  .c{
    content: '';
    width: 150px;
    height: 150px;
    background: #7B3F61;
    border-radius: 50%;
    position: absolute;
    top: 75;
  }
  .lc {
    left: 75;
  }
  .rc {
    background: #E78481;
    left: 175;
    overflow: hidden;
  }
  .inner {
    background: #09042A;
    top: 0;
    left: -100;
  }
</style>

```
