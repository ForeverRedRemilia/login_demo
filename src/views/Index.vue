<template>
  <div>
    <Header></Header>
    <LoginForm></LoginForm>
  </div>
</template>

<script>
import Header from '../components/index/Header'
import LoginForm from '@/components/LoginForm'
export default {
  name: 'Index',
  components: {
    LoginForm,
    Header
  }
}
</script>

<style scoped>
.root-div{
  height: 100%;
  width: 100%;
}
</style>
