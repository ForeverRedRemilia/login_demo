<template>
  <div>
    <Header></Header>
    fuck you
    <HelloWorld></HelloWorld>
    fuck you
  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld'
import Header from '../components/index/Header'
export default {
  name: 'Index',
  components: {
    Header,
    HelloWorld
  }
}
</script>

<style scoped>
.root-div{
  height: 100%;
  width: 100%;
}
</style>
