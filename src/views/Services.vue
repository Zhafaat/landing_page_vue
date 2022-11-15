<template>
    <div class="services">
        <ServicesHeaderVue/>
        <ServicesAchievementVue/>
        <ServicesProductVue/>
        
    </div>
</template>

<script>
import ServicesHeaderVue from '@/components/services/ServicesHeader.vue';
import ServicesAchievementVue from '@/components/services/ServicesAchievement.vue';
import ServicesProductVue from '@/components/services/ServicesProduct.vue';
    export default {
        name: 'Services',
        components: {
            ServicesHeaderVue,
            ServicesAchievementVue,
            ServicesProductVue
        }
    }
</script>

<style>
.services {
    width: 1200px;
    max-width: 1200px;
    margin-inline: auto;
    display: flex;
    flex-direction: column;
}


</style>