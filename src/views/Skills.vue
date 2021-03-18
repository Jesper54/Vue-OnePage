<template>
  <div class="skills">
    <Header />
    <div class="skills">
      <h1>Skills</h1>
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
@import "@/assets/styles/Skills.scss";
</style>
