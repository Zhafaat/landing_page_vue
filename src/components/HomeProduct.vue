<template>
    <div class="home-product">
      <div class="home-product-top">
        <p class="home-product-title">PRODUCT</p>
        <div class="home-product-content-bg">
          <p class="home-product-content">Choose your product themes.</p>
          <p class="home-product-text">Find the theme you want. If our choice of theme is not what you want, you can customize it as you want.</p>
        </div>
      </div>
      <div class="home-product-bottom">
        <HomeProductListVue number="01" text="Vintage" />
        <HomeProductListVue number="02" text="Minimalist" />
        <HomeProductListVue number="03" text="Modern" />
        <HomeProductListVue number="04" text="Transitional" />
      </div>
    </div>
</template>

<script>
  import HomeProductListVue from './HomeProductList.vue';
    export default {
        name: 'home product',
        components: {
          HomeProductListVue
        }
    }
</script>

<style>
.home-product {
  height: 876px;
  margin-top: 160.45px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  /* background-color:aqua; */
  /* position: relative; */
}

.home-product-top {
  height: 166px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.home-product-title {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  margin: 0;
  color: #333333;
}

.home-product-content-bg {
  width: 1200px;
  display: flex;
  justify-content: space-between;
  /* margin: 20px 0 0 0; */
}

.home-product-content {
  width: 337px;
  /* height: 122px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 0;
}

.home-product-text {
  align-self: center;
  width: 473px;
  margin: 0;
  /* height: 87px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
}

.home-product-bottom {
  height: 637px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>