<template>
  <div class="col-md-4">
    <div class="card">
      <div class="card-header">
        <h2>{{ title }}</h2>
        <h4>{{ cardsSection.title }}</h4>
      </div>
      <div class="card-body">
        <p class="snippet">{{ cardsSection.snippet }}</p>
      </div>
    </div>
    <div class="header"></div>
  </div>
</template>

<script>
export default {
  name: "LargeCardDisplay",
  props: ["cardsSection"],
};
</script>

<style scoped>
.card {
  margin-top: 2rem;
}
.header {
  font-weight: 700;
  font-size: 1.5rem;
}
.snippet {
  color: grey;
  margin-bottom: 1.5rem;
}
</style>
