<template>
  <div>
    <el-input placeholder="请输入用户名/手机号" v-model="userName" class="login-form-input"></el-input>
    <br>
    <el-input placeholder="请输入密码" v-model="password" class="login-form-input"></el-input>
  </div>
</template>

<script>
export default {
  name: 'LoginForm',
  data () {
    return {
      userName: '',
      password: ''
    }
  }
}
</script>

<style scoped>
@import "../style/index.css";
</style>
