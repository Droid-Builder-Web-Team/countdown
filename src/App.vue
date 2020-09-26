<template>
  <div id="app">
    <img alt="Vue logo" class="inline img-fluid" src="./assets/Baddeley2020.png" style="width:300px; height:300px;">
    <HelloWorld msg="Welcome to Your Vue.js App"/>


    <img alt="Vue logo" class="inline img-fluid" src="./assets/dbwtlogo.png" style="width:300px; height:400px;">
  </div>
</template>

<script>
import HelloWorld from './views/Home.vue'

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
  color: #FFF;
  height:100vh;
  width:100%;
  background: linear-gradient(180deg, #101430 0%, black 100%);

}
</style>
