<template>
  <div class="home">
      <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->  
    <HomeHeaderVue/>
    <HomeAboutVue/>
    <HomeServiceVue/>
    <HomeProductVue/>
    <HomeMaterialVue/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeaderVue from '@/components/HomeHeader.vue';
import HomeAboutVue from '@/components/HomeAbout.vue';
import HomeServiceVue from '@/components/HomeService.vue';
import HomeProductVue from '@/components/HomeProduct.vue';
import HomeMaterialVue from '@/components/HomeMaterial.vue';
export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HomeHeaderVue,
    HomeAboutVue,
    HomeServiceVue,
    HomeProductVue,
    HomeMaterialVue
  }
}
</script>

<style>

.home {
  width: 1200px;
  max-width: 1200px;
  margin-inline: auto;
  display: flex;
  flex-direction: column;
}

</style>
