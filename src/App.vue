<template>
  <div class="container">
    <Flyer flyer="../assets/flyer1.jpeg" />
    <Guidelines />
    <InstagramIcon class="social-icon" user="reunition.party" />
    <FacebookIcon class="social-icon" user="re.unitionparty" />
  </div>
</template>

<script>
import Flyer from './components/Flyer.vue';
import Guidelines from './components/Guidelines.vue';
import InstagramIcon from './components/InstagramIcon.vue';
import FacebookIcon from '@/components/FacebookIcon';

export default {
  name: 'App',
  components: {
    FacebookIcon,
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
.container {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
}

.social-icon {
  width: 48px;
  height: 48px;
  margin-right: 16px;
}
</style>
