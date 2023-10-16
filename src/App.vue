<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="asdasd! It is your project...!!!"/>
  <DosenpaiQwwewe/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import DosenpaiQwwewe from "@/components/DosenpaiQwwewe.vue";

export default {
  name: 'App',
  components: {
    HelloWorld,
    DosenpaiQwwewe,
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
