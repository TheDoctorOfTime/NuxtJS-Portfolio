<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from '../pages/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="css">

#app {
  scroll-behavior: auto;
  overflow-x: hidden;
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #FCEADE;
  margin: -0.5em;
  padding-top: 0.5em;
  padding-bottom: 15em;
}

html{
  scroll-behavior: smooth;
}

</style>
