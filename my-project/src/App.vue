<template>
  <div id="app">
    <img style="width:100%" alt="Vue logo" src="./assets/wallhaven.jpg">
    <HelloWorld msg="asdkfjsdfasjdfasl;dj"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.bg {
  width: 100%;
  /* height: 500px */
}
</style>
