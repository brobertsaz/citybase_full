<template>
  <v-app>
      <div id="app">
    <Form />
  </div>
  </v-app>

</template>

<script>

import Form from './components/Form.vue'

export default {
  name: 'app',
  components: {
    Form
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
