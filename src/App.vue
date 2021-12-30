<template>
  <div>
  <Sample />
  <HelloWorld />
  <Input />
  </div>
</template>

<script>

import Sample from './components/Sample.vue'
import HelloWorld from './components/HelloWorld.vue'
import Input from './components/Input.vue'

export default {
  name: 'App',
  components: {
    Sample,
    HelloWorld,
    Input
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
