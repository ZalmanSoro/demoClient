<template>
  <v-app>
    <div id="app">
      <v-app>
      <v-content>
        <my-component>
      </v-content>
    </v-app>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import myComponent from './components/myComponent.vue'
export default {
  name: 'app',
  components: {
    myComponent:myComponent
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
