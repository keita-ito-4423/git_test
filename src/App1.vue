<template>
  <div id="app1">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="111 Hi my first vue!!!"/>
    <HelloWorld1 msg="111 Hi my first vue!!! my hello world!!!"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorld1 from './components/HelloWorld1.vue'

export default {
  name: 'App1',
  components: {
    HelloWorld,
    HelloWorld1,
  }
}
</script>

<style>
#app1 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
