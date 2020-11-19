<template>
  <div style=" display: flex; flex-direction: column; justify-content: center;align-items: center; margin-top: 80px">
    <img alt="Vue logo" src="./assets/logo.png" style="width: 400px;">
    <HelloWorld />
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
</style>
