<template>
    <div class="services-header">
        <p class="services-header-title">Services</p>
        <p class="services-header-text">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        <img class="services-header-image" src="../../assets/unsplash_services1.svg" alt="services image">
    </div>
</template>

<script>
    export default {
        name: 'servis header'
    }
</script>

<style>
.services-header {
    height: 771px;
    margin: 100px 0 0 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    /* background-color: aqua; */
}

.services-header-title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 78px;
    color: #000000;
    margin: 0;
}

.services-header-text {
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

.services-header-image {
    width: 1200px;
    height: 513px;
    margin: 0;
}
</style>