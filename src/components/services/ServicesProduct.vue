<template>
    <div class="services-product">
        <div class="services-product-top">
            <p class="services-title">PRODUCT</p>
            <div class="services-product-head">
                <p class="services-product-content">Choose your product themes.</p>
                <p class="services-product-text">Find the theme you want. If our choice of theme is not what you want, you can customize it as you want.</p>
            </div>
        </div>
        <div class="services-product-bottom">
            <div class="services-product-bg-subcontent">
                <p class="services-product-subcontent">01</p>
                <div>
                    <p class="services-product-subcontent">Vintage</p>
                    <p class="services-product-subcontent-text">the use of simple and limited elements to get the best effect or impression.</p>
                </div>
            </div>
            <div class="services-product-bg-subcontent">
                <p class="services-product-subcontent">02</p>
                <div>
                    <p class="services-product-subcontent">Minimalist</p>
                    <p class="services-product-subcontent-text">the use of simple and limited elements to get the best effect or impression.</p>
                </div>
            </div>
            <div class="services-product-bg-subcontent">
                <p class="services-product-subcontent">03</p>
                <div>
                    <p class="services-product-subcontent">Modern</p>
                    <p class="services-product-subcontent-text">the use of simple and limited elements to get the best effect or impression.</p>
                </div>
            </div>
            <div class="services-product-bg-subcontent">
                <p class="services-product-subcontent">04</p>
                <div>
                    <p class="services-product-subcontent">Transitional</p>
                    <p class="services-product-subcontent-text">the use of simple and limited elements to get the best effect or impression.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'services product'
}
</script>

<style>
    .services-product {
        height: 876px;
        margin: 100px 0 3px 0;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        /* background-color: aqua; */
    }

    .services-product-head {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 1200;
        margin: 20px 0 0 0;
    }

    .services-product-content {
        width: 337px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 36px;
        line-height: 61px;
        color: #333333;
        margin: 0;
    }
    
    .services-product-text {
        width: 473px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        color: #9C9C9C;
        margin: 0;
    }

    .services-product-bottom {
        height: 637px;
        /* background-color: bisque; */
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .services-product-bg-subcontent {
        display: flex;
    }

    .services-product-subcontent {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 32px;
        line-height: 45px;
        color: #333333;
        margin: 0 87px 0 0;
    }

    .services-product-subcontent-text {
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