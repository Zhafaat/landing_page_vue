<template>
    <div class="contact-header">
        <p class="contact-header-title">Contact Us</p>
        <p class="contact-header-text">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>

    </div>
</template>

<script>
    export default {
        name: 'contact header'
    }
</script>

<style>
.contact-header {
    height: 205px;
    margin: 100px 0 0 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}

.contact-header-title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 78px;
    color: #000000;
    margin: 0;
}

.contact-header-text {
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
</style>