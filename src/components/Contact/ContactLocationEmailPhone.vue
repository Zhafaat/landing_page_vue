<template>
    <div class="email-phone">
        <p class="media">{{media}}</p>
        <p class="adress">{{adress}}</p>
    </div>
</template>

<script>
    export default {
        name: 'contact location email phone',
        props: {
            media: String,
            adress: String
        }
    }
</script>

<style>
    .email-phone {
        height: 73px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .media {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 34px;
        color: #333333;
        margin: 0;
    }

    .adress {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        color: #9C9C9C;
        margin: 0;
    }
</style>