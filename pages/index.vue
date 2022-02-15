<template>
  <div class="container">
    <Header title="Yeah" link="hi" />
    <Hero />
    <div class="row">
      <LargeCardDisplay
        v-for="cardInfo in largeCardInfo"
        :key="cardInfo.id"
        :cardsSection="cardInfo"
      />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import { largeCardSections } from "../assets/data.js";
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
    };
  },
};
</script>

<style></style>
