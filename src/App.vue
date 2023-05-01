<template>
  <Header />
  <main
    class="relative min-h-screen max-w-screen-xl mx-auto bg-white bg-opacity-80 shadow-2xl"
  >
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

<style>
#app {
  min-height: 100vh;
}
body {
  background-image: url("../BGimg.jpg");
  background-position: center;
  background-size: cover;
  background-color: aquamarine;
  background-repeat: no-repeat;
}
</style>
