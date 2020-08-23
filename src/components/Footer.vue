<template>
  <footer class="footer">
    <h2>Made with &#x1F496; and GSAP &#x26A1;</h2>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.footer {
  flex: 1 0 1;
  min-height: 80px;
  background-color: teal;
  text-align: center;
  color: white;
  padding: 1em;

  .footer-content {
    width: 100%;
    max-width: 1400px;
    margin: 0 auto;
  }
}
</style>