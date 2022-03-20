<template>
  <a href="https://instagram.com/re.un1t1on" target="_blank">
    <img alt="link to instagram" src="../assets/insta-white.png" />
  </a>
</template>

<script>
export default {
  name: 'InstagramIcon',
  props: {
    user: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  width: 48px;
  height: 48px;
}
</style>
