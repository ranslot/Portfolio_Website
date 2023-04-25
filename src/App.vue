<script>
import Header from "./components/App_header.vue";
import Footer from "./components/App_footer.vue";

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<template>
  <Header />

  <main>
    <router-view />
  </main>

  <Footer />
</template>

<style scoped>
#app {
  height: 100vh;
}
</style>
