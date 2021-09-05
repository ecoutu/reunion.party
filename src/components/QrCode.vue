<template>
  <a class="flex-row" href="https://reunition.party/" target="_blank">
    <img class="qrcode" alt="link to qrCode" src="../assets/qr.png" />
  </a>
</template>

<script>
export default {
  name: 'QrCode',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.qrcode {
  width: 128px;
  height: 128px;
}
</style>
