<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<h1>{{ msg }}</h1>-->
    <!--<router-view/>-->
    <firstDemo></firstDemo>
  </div>
</template>

<script>
import firstDemo from './components/firstDemo'
export default {
  name: 'App',
  data () {
    return {
      msg: 'title'
    }
  },
  components: {firstDemo}
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
