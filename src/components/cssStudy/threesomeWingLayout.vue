<!--  -->
<template>
  <div class="contain">
    <h1>双飞翼布局</h1>
    <div id="main" class="col">
      <div id="main-wrap">this is main</div>
    </div>
    <div id="left" class="col">this is left</div>
    <div id="right" class="col">this is right</div>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  }
}
</script>
<style lang='scss' scoped>
  .contain {
    min-width: 550px;
  }

  .col {
    float: left;
  }

  #main {
    width: 100%;
    height: 200px;
    background-color: #ccc;
  }

  #main-wrap {
    margin: 0 190px 0 190px;
  }

  #left {
    width: 190px;
    height: 200px;
    background-color: #0000ff;
    margin-left: -100%;
  }

  #right {
    width: 190px;
    height: 200px;
    background-color: #ff0000;
    margin-left: -190px;
  }
</style>
