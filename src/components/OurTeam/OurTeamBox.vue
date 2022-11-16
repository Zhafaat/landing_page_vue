<template>
    <div class="box-bg">
        <img class="box-image" src="../../assets/circle.svg" alt="gray circle">
        <p class="box-content">{{ title }}</p>
        <p class="box-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
    </div>
</template>

<script>
    export default {
        name: 'our team box',
        props: {
            title: String
        }
    }
</script>

<style>
    .box-bg {
        width: 388px;
        height: 295px;
        background: #FFFFFF;
        box-shadow: 0px 0px 5px 1px rgba(0, 0, 0, 0.1);
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
    }

    .box-image {
        width: 63px;
        height: 63px;
        margin: 0;
    }

    .box-content {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 34px;
        color: #333333;
        margin: 0;
    }
    
    .box-text {
        width: 334px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        text-align: center;
        color: #9C9C9C;
        margin: 0;
    }
</style>