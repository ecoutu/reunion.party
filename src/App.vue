<template>
  <div class="container flex-column">
    <Flyer flyer="../assets/flyer1.jpeg" />
    <Guidelines />
    <div class="flex-row">
      <InstagramIcon class="social-icon" user="reunition.party" />
      <FacebookIcon class="social-icon" user="re.unitionparty" />
    </div>
    <div class="flex-row">
      <QrCode class="qrcode" />
    </div>
  </div>
</template>

<script>
import Flyer from './components/Flyer.vue';
import Guidelines from './components/Guidelines.vue';
import InstagramIcon from './components/InstagramIcon.vue';
import FacebookIcon from '@/components/FacebookIcon';
import QrCode from '@/components/QrCode';

export default {
  name: 'App',
  components: {
    FacebookIcon,
    Flyer,
    Guidelines,
    InstagramIcon,
    QrCode,
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
  color: #2c3e50;
}

.social-icon {
  width: 48px;
  height: 48px;
  margin: 16px;
}

.flex-column {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.flex-row {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>
