<template>
  <div id="app">
    
    <filepicker/>
  </div>
</template>

<script>
import filepicker from './components/FilePicker.vue'

export default {
  name: 'app',
  components: {
    filepicker
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
  padding: 20px;
}


body {
  background-color: #ffffff;
}
</style>
