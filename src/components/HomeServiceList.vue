<template>
    <div class="servis-list">
        <p class="servis-list-number">{{number}}</p>
        <p class="servis-list-text">{{text}}</p>
    </div>
</template>

<script>
    export default {
        name: 'home service list',
        props: {
            number: String,
            text: String
        }
    }
</script>

<style>
.servis-list {
    display: flex;
}

.servis-list-number {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 34px;
    color: #333333;
    margin: 0 40px 0 0 
}

.servis-list-text {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 34px;
    color: #333333;
    margin: 0;
}
</style>