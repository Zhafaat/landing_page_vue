<template>
    <div class="card">
        <img :src="require('@/assets/' + image + '')" alt="ceo image">
        <div class="card-nameTag">
            <p class="card-nameTag-name">Shoo Phar Dhie</p>
            <p class="card-nameTag-position">CEO</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'card',
        props: {
            image: String
        }
    }
</script>

<style>
    .card {
        width: 282px;
        height: 400px;
        background: #2C3878;
        margin: 0;
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
        align-items: center;
        position: relative;
    }

    .card-nameTag {
        width: 258px;
        height: 96px;
        background: #FFFFFF;
        display: flex;
        flex-direction: column;
        justify-content: center;
        /* align-items: center; */
        position: absolute;
        top: 292px;
    }

    .card-nameTag-name {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 34px;
        color: #333333;
        margin: 0 0 0 16px;
    }

    .card-nameTag-position {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 26px;
        color: #9C9C9C;
        margin: 0 0 0 16px;
    }
</style>