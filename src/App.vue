<template>
  <div class="page">
    <NavbarVue/>
    <router-view></router-view>
    <BottomVue/>
  </div>
</template>

<script>
import NavbarVue from './components/Navbar.vue';
import BottomVue from './components/Bottom.vue';
export default {
  name: 'app',
  components: {
    NavbarVue,
    BottomVue
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
body {
  margin: 0;
  /* background-color: #D9D9D9; */
}

.page {
  max-width: 1440px;
  min-width: 1200px;
  width: 100vw;
  /* background-color: aqua; */
  margin: 0 auto;
}


</style>
