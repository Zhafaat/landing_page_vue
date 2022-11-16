<template>
    <div class="ourTeam-header">
        <p class="ourTeam-header-title">Our Teams</p>
        <p class="ourTeam-header-text">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        <img class="ourTeam-header-image" src="../../assets/unsplash_ourteam1.svg" alt="our team image">
    </div>
</template>

<script>
    export default {
        name: 'our team'
    }
</script>

<style>
.ourTeam-header {
    height: 771px;
    margin: 100px 0 0 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    /* background-color: aqua; */
}

.ourTeam-header-title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 78px;
    color: #000000;
    margin: 0;
}

.ourTeam-header-text {
    width: 518px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    text-align: center;
    color: #000000;
    margin: 0;
}

.ourTeam-header-image{
    width: 1200px;
    height: 513px;
}
</style>