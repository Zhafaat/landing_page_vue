<template>
    <div class="ourTeam-Designer">
        <div class="ourTeam-Designer-top">
            <p class="ourTeam-title">Designer</p>
            <p class="ourTeam-content">Creative Person</p>
            <p class="ourTeam-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        </div>
        <div class="ourTeam-Designer-bg-card">
            <div class="bg-card">
                <OurTeamCardVue image="ceo1.svg"/>
                <OurTeamCardVue image="ceo2.svg"/>
                <OurTeamCardVue image="ceo3.svg"/>
                <OurTeamCardVue image="ceo4.svg"/>
            </div>
            <div class="bg-card">
                <OurTeamCardVue image="ceo5.svg"/>
                <OurTeamCardVue image="ceo6.svg"/>
                <OurTeamCardVue image="ceo7.svg"/>
                <OurTeamCardVue image="ceo8.svg"/>
            </div>
        </div>
    </div>
</template>

<script>
import OurTeamCardVue from '../../components/OurTeam/OurTeamCard.vue';
    export default {
        name: 'our team designer',
        components: {
            OurTeamCardVue
        }
    }
</script>

<style>
    .ourTeam-Designer {
        height: 1119px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        /* background-color: aqua; */
        margin: 100px 0 0 0;
    }

    .ourTeam-Designer-top {
        height: 216px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .ourTeam-title {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 24px;
        color: #000000;
        margin: 0;
    }

    .ourTeam-content {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 36px;
        line-height: 61px;
        color: #333333;
        margin: 0;
    }

    .ourTeam-text {
        width: 471px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        color: #9C9C9C;
        margin: 0;
    }

    .ourTeam-Designer-bg-card {
        height: 824px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .bg-card {
        width: 1200px;
        display: flex;
        justify-content: space-between;
    }
</style>