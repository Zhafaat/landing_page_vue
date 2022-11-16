<template>
    <div class="ourTeam">
        <OurTeamHeaderVue/>
        <OurTeamDesignerVue/>
        <OurTeamServiceVue/>
    </div>
</template>

<script>
import OurTeamHeaderVue from '@/components/OurTeam/OurTeamHeader.vue';
import OurTeamDesignerVue from '@/components/OurTeam/OurTeamDesigner.vue';
import OurTeamServiceVue from '@/components/OurTeam/OurTeamService.vue';
    export default {
        name: 'our team',
        components: {
            OurTeamHeaderVue,
            OurTeamDesignerVue,
            OurTeamServiceVue
        }
    }
</script>

<style>
    .ourTeam {
        width: 1200px;
        max-width: 1200px;
        margin-inline: auto;
        display: flex;
        flex-direction: column;
    }
</style>