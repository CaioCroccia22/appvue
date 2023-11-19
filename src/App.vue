
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!--Feita a importação do Helloworld.vue é possível referênciar ela no template do Vue.js-->
    <!--Após isso temos o atributo msg, que é criado manualmente para receber um valor-->
    <HelloWorld msg="Olá mundo"/>
  </div>
</template>

<script>
/*Importação do componente Hello world.vue no script*/
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    /*Alem da importação do componente Hello world no script, temos sua declaração aqui no components também*/
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
  margin-top: 60px;
}
</style>
