# [Target #43 - Wrench](https://cssbattle.dev/play/43)

![](https://cssbattle.dev/targets/43.png)

```HTML
<!-- Battle #8 - Transition/ #43 - Wrench -->
<div class="hook l-hook"></div>
<div class="hook r-hook"></div>
<div class="cov cover1"></div>
<div class="cov cover2"></div>

<style>
  body {
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .hook {
    width: 100px;
    height: 180px;
    background: transparent;
    border: 30px solid #243D83;
    border-radius: 0 70px 70px 0;
    position: absolute;
  }
  .l-hook {
    left: 55;
  }
  .r-hook {
    left: 185;
    transform: rotate(180deg);
  }
  .cov {
    width: 145px;
    height: 300px;
    background: #6592CF;
    position: absolute;
  }
  .cover1 {
    left: 0;
  }
  .cover2 {
    right: 0;
  }
</style>

```
