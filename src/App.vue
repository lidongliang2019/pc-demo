<template>
  <div id="app">
<HomePage></HomePage>
  </div>
</template>

<script>
 import HomePage from "./components/HomePage";
    export default {
        name: 'App',
        components: {
            HomePage
        }
    }

</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    margin-top: 0;
    width: 100%;
    overflow: hidden;
    background-color: #f8f8f8;
  }
body{
  margin: 0;
}
</style>
