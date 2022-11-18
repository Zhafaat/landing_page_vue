<template>
    <div class="city">
        <p class="city-name">{{cityName}}</p>
        <p class="city-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
    </div>
</template>

<script>
    export default {
        name: 'contact location city',
        props: {
            cityName: String
        }
    }
</script>

<style>
    .city {
        width: 334px;
        height: 180px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .city-name {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 34px;
        color: #333333;
        margin: 0;
    }

    .city-text {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        color: #9C9C9C;
        margin: 0;

    }
</style>