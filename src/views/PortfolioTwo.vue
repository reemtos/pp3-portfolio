<template>
  <div class="two main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/one">
      <img src="../assets/arrow-up.svg" alt="" class="arrow arrow-up"></router-link>
      
      <h1>Mobile UI</h1>
      
      <p class="subtxt">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      <p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      
      <router-link to="/portfolio/three">
      <img src="../assets/arrow-down.svg" alt="" class="arrow arrow-down"></router-link>
    </div>
    
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>
export default {
  name: 'two'
};
</script>

<style lang="scss" scoped>
$page_color: #48b886;

h1 {
  color: $page_color !important;
}

.img2 {
  background: url('../assets/phone.jpg');
  background-size: cover;
  background-position: 50%;

  img {
    width: 50%;
  }
}
</style>