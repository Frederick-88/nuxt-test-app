<template>
  <div class="app">
    <Navbar />
    <Nuxt />
  </div>
</template>

<script>
import NuxtLogo from "../components/NuxtLogo";
import Navbar from "../components/Navbar";

export default {
  components: {
    NuxtLogo,
    Navbar,
  },
};
</script>

<style>
.app {
  padding: 2rem 5rem;
}
.nuxt__text {
  color: #39b982;
}
</style>
