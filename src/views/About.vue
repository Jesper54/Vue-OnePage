<template>
  <div class="page">
    <Header />
    <div class="about">
      <h1>Over Mij</h1>
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
@import "@/assets/styles/About.scss";
</style>
