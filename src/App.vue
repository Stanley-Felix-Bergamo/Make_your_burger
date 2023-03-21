<template>
  <Navbar />
  <router-view />
  <Footer />
</template>

<script lang="js">
import Navbar from './components/Navbar.vue';
import Footer from './views/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
  }
}
</script>

<style></style>
