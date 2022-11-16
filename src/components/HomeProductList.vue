<template>
    <div class="product-list">
        <div>
            <p class="product-list-number">{{number}}</p>
        </div>
        <div>
            <p class="product-list-content">{{text}}</p>
            <p class="product-list-text">the use of simple and limited elements to get the best effect or impression.</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'home product list',
        props: {
            number: String,
            text: String
        }
    }
</script>

<style>
.product-list {
    display: flex;
}

.product-list-number {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 45px;
    color: #333333;
    margin: 0 87px 0 0 
}

.product-list-content {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 45px;
    color: #333333;
    margin: 0;
}

.product-list-text {
    width: 469px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    color: #333333;
    margin: 24px 0 0 0;
}
</style>