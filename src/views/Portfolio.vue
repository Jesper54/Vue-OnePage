<template>
  <div class="portfolio">
    <Header />
    <div class="portfolio">
      <h1>Portfolio</h1>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Footer from "../components/Footer.vue";

export default {
  components: {
    Header,
    Footer
  }
};
</script>

<style scoped lang="scss">
@import "@/assets/styles/Portfolio.scss";
</style>
