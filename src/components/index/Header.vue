<template>
  <div>
    <div class="header-div">
      <span class="header-span"><a><i class="el-icon-question"></i>帮助</a></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  .header-div {
    /*background-size: 4096px;*/
    line-height: 36px;
    margin: 0 auto;
    background-color: #FFF0F5;
    text-align: right;
    /*background-image: url("../../desktop.jpg");*/
  }

  .header-span {
    margin-right: 30px;
    vertical-align: middle;
  }
</style>
