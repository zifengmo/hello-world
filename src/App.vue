<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="最迷人的最危险"/>
  </div>
</template>

<script>
import HelloWorld from './components/First.vue';
import PP from './components/Post.vue';


export default {
  name: 'app',
  components: {
    HelloWorld,
      PP
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
