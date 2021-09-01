<template>
  <div class="app">
    <Flyer flyer="../assets/flyer1.jpeg" />
    <Guidelines />
    <InstagramIcon class="instagram-icon" user="reunition.party" />
  </div>
</template>

<script>
import Flyer from './components/Flyer.vue';
import Guidelines from './components/Guidelines.vue';
import InstagramIcon from './components/InstagramIcon.vue';

export default {
  name: 'App',
  components: {
    Flyer,
    Guidelines,
    InstagramIcon,
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

.instagram-icon {
  width: 48px;
  height: 48px;
  stroke: white;
}
</style>
