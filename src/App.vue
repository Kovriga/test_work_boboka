<template>
  <img alt="logo" src="./assets/Group17.svg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <button-push-messeng/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ButtonPushMesseng from "@/components/ButtonPushMesseng";

export default {
  name: 'App',
  components: {
    ButtonPushMesseng,
    HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
  background: #1E1E1E;
  height: 100%;
}
body {
  overflow: hidden;
  margin: 0;
  height: 100vh;
}
</style>
<style scoped>
img {
  margin-top: 2em;
  width: 25%;
}
</style>
