<template>
  <Header />

  <main class="min-h-screen max-w-screen-xl mx-auto bg-cyan-100">
    <router-view />
  </main>

  <Footer />
</template>

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

<style scoped>
#app {
  height: 100vh;
}
</style>
