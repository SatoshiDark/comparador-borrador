<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Auditoria del Pueblo"/>
    <!-- <main-form /> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import MainForm from './components/MainForm.vue'

export default {
  name: 'app',

  components: {
    HelloWorld,
    // MainForm
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
