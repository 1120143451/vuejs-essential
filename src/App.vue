<template lang="pug">
  div#app
    img(src="./assets/logo.png")
    h1 Welcome from pug & sass
    HelloWorld
  <!-- <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
  </div> -->
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  h1 {
    color: #42b983;
  }
}
</style>
