<template>
  <div>
    <NavbarVue/>
    <router-view/>
  </div>
</template>

<script>
import NavbarVue from './components/Navbar.vue';
export default {
  name: 'app',
  components: {
    NavbarVue
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');
body {
  margin: 0;
  /* background-color: #D9D9D9; */
}

.margin {
  max-width: 1440px;
  width: 100vw;
  /* background-color: aqua; */
  /* margin-left: 120px; */
  /* margin-right: 120px; */
  margin-inline: auto;
}
</style>
