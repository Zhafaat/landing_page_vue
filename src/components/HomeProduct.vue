<template>
    <div class="home-product">
      <div class="home-product-top">
        <p class="font-subcontent">PRODUCT</p>
        <div class="product-title">
          <p class="font-product-content">Choose your product themes.</p>
          <p class="font-product-text">Find the theme you want. If our choice of theme is not what you want, you can customize it as you want.</p>
        </div>
      </div>
      <div class="home-product-bottom">
        <table class="product-table">
          <tr>
            <td class="td-product">01</td>
            <td class="td-product">Vintage</td>
          </tr>
          <tr>
            <td></td>
            <td class="td-text">the use of simple and limited elements to get the best effect or impression.</td>
          </tr>
          <tr>
            <td class="td-product">02</td>
            <td class="td-product">Minimalist</td>
          </tr>
          <tr>
            <td></td>
            <td class="td-text">the use of simple and limited elements to get the best effect or impression.</td>
          </tr>
          <tr>
            <td class="td-product">03</td>
            <td class="td-product">Modern</td>
          </tr>
          <tr>
            <td></td>
            <td class="td-text">the use of simple and limited elements to get the best effect or impression.</td>
          </tr>
          <tr>
            <td class="td-product">04</td>
            <td class="td-product">Transitional</td>
          </tr>
          <tr>
            <td></td>
            <td class="td-text">the use of simple and limited elements to get the best effect or impression.</td>
          </tr>
         
        </table>
      </div>
    </div>
</template>

<script>
    export default {
        name: 'home product'
    }
</script>

<style>
.home-product {
  margin-top: 522px;
  display: flex;
  flex-direction: column;
  position: relative;
}

.product-title {
  width: 1200px;
  display: flex;
  justify-content: space-between;
  /* margin: 20px 0 0 0; */
}

.font-product-content {
  width: 337px;
  height: 122px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 20px 0 0 0;
}

.font-product-text {
  width: 473px;
  height: 87px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
  margin: 34px 0 0 0;
}

.product-table {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 45px;
  color: #333333;
  margin: 73px 0 0 0;
  
}

.td-product {
  padding: 0;
  padding-right: 87px;
  padding-bottom: 24px;
}

.td-text {
  width: 469px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #333333;
  padding-bottom: 43px;
}

</style>