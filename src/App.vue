<template>
  <div id="app">
    <b-container fluid class="p-4">
      <b-row class="vh-100 text-center" align-v="center">
        <b-col>
              <img alt="Michael Baddeley Printed Droids Group Logo" id="logo" class="img-fluid" src="./assets/Baddeley2020.png" style="width:300px; height:300px;">
        </b-col>

        <b-col>
          <HelloWorld msg="Welcome to Your Vue.js App"/>
        </b-col>

        <b-col>
              <img alt="Droid Builder Web Team Logo" id="logo" class="img-fluid" src="./assets/dbwtlogo.png" style="width:300px; height:400px;">
        </b-col>
      </b-row>
    </b-container>
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

#logo{
  display:inline;
  vertical-align: middle;
}
</style>
