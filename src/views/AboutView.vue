<template>
  <div class="about">
    <AboutHeaderVue/>
    <AboutAchievementVue/>
    <AboutServiceVue/>
  </div>
</template>

<script>
import AboutHeaderVue from '@/components/AboutHeader.vue';
import AboutAchievementVue from '@/components/AboutAchievement.vue';
import AboutServiceVue from '@/components/AboutService.vue';
export default {
  name: 'AboutView',
  components: {
    AboutHeaderVue,
    AboutAchievementVue,
    AboutServiceVue
  }
}
</script>

<style>
.about {
  width: 1200px;
  max-width: 1200px;
  margin-inline: auto;
  display: flex;
  flex-direction: column;
}

.font-400 {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  margin: 0;
}
.font-500 {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  margin: 0;
}
.font-600 {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  margin: 0;
}
.font-700 {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  margin: 0;
}


</style>
