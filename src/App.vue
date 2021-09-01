<template>
  <div class="app">
    <Flyer flyer="../assets/flyer1.jpeg" />
    <Guidelines />
  </div>
</template>

<script>
import Flyer from './components/Flyer.vue';
import Guidelines from './components/Guidelines.vue';

export default {
  name: 'App',
  components: {
    Flyer,
    Guidelines,
  },
};
</script>

<style>
html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
  background: black;
}
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}
</style>
