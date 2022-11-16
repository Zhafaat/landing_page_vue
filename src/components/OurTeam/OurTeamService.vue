<template>
    <div class="ourTeam-service">
        <div class="ourTeam-service-top">
            <p class="ourTeam-title">SERVICE</p>
            <p class="ourTeam-content">Why Choose Us</p>
            <p class="ourTeam-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        </div>
        <div class="ourTeam-service-bottom">
            <OurTeamBoxVue title="High Quality"/>
            <OurTeamBoxVue title="Professional Designer"/>
            <OurTeamBoxVue title="The Best Services"/>
        </div>
    </div>
</template>

<script>
import OurTeamBoxVue from './OurTeamBox.vue';
export default {
    name: 'our team service',
    components: {
        OurTeamBoxVue,
    }
}
</script>

<style>
.ourTeam-service {
    height: 551px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 100px 0 1px 0;
    /* background-color: aqua; */
}

.ourTeam-service-top {
    height: 216px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 0;
}

.ourTeam-service-bottom {
    width: 1200px;
    display: flex;
    justify-content: space-between;
}
</style>