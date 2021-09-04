<template>
  <a href="https://www.facebook.com/re.unitionparty/" target="_blank">
    <img alt="link to facebook" src="../assets/facebook.png" />
  </a>
</template>

<script>
export default {
  name: 'FacebookIcon',
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
