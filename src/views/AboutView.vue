<template>
  <AboutVue />
  <div class="about-page" style="background-image: url();">
    <div class="about-page-content">
      <h1 class="text-white">About Me</h1>
      <p class="text-white"></p>
  </div>
  </div>
</template>

<script>
import AboutVue from '@/components/AboutVue.vue';
export default {
  components: {
    AboutVue
}
}
</script>
<style scoped>
  .about-page {
    background-position: center;
    background-size: cover;
    min-height: 100vh;
    z-index: ;
  }

  .about-page-content {
    padding: 2rem;
  }

  .text-white {
    color: white;
  }
 
</style>