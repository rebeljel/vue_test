<template>
  <div class="hero container">
    <div class="text-container">
      <h1 class="header">Living indoors made healthy</h1>
      <p class="snippet">
        An app that tunes temperature and humidity levels for a healthier indoor
        life
      </p>
      <button class="button btn">Get more info</button>
    </div>
    <img src="~assets/hero.png" alt="" class="image" />
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
.hero {
  height: 50vh;
  position: relative;
  display: flex;
  padding: 5rem 0;
  align-items: flex-start;
  justify-content: space-between;
}
.text-container {
  width: 50%;
  margin-top: 4rem;
}
.header {
  font-weight: 900;
  font-size: 5rem;
}
.snippet {
  color: grey;
  font-size: 1.25rem;
}
.image {
  width: 27.5rem;
  margin-top: 2rem;
}
.overlay {
  background: rgba(0, 0, 0, 0);
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
}
.button {
  padding: 1rem 4rem;
  border-radius: 100rem;
  background-color: #3e7a65;
  color: white;
  width: 20rem;
  font-weight: 700;
  transition: 0.5s;
}
.button:hover {
  width: 21.5rem;
}
@media (max-width: 500px) {
  .hero {
    height: 40vh;
  }
}
</style>
