<template>
  <header>
    <h1>{{ title }}</h1>
    <a href="#">Yoyo</a>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: ["title", "link"],
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-bottom: 20px;
}
</style>
