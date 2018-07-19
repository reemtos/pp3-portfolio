<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Crypto Logo</h1>
      <p class="subtxt">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      <p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      
      <router-link to="/portfolio/two">
      <img src="../assets/arrow-down.svg" alt="" class="arrow arrow-down"></router-link>
    </div>
    
    <div class="right-content img2">
      <img src="../assets/logo.svg" alt="">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'one',
  components: {
    HelloWorld
  }
};
</script>

<style lang="scss" scoped>
$page_color: #625b7e;

h1 {
  color: $page_color !important;
}

.img2 {
  background: $page_color;

  img {
    width: 50%;
  }
}
</style>