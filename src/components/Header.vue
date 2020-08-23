<template>
  <header class="header">
    <div class="brand">&#x1F346; EggPlant Group</div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 60px;
  background: teal;
  padding: 0 1rem;
  display: flex;
  color: #f5f5f5;
  align-items: flex-end;

  .brand {
    font-size: 2rem;
    padding-bottom: 0.375rem;
  }
}
</style>
