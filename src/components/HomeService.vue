<template>
    <div class="home-service">
      <div class="home-service-top">
        <div>
          <p class="font-subcontent">SERVICE</p>
        </div>
        <p class="font-service-content">attractive furniture with the best quality.</p>
        <p class="font-service-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        <div class="servis-top-table">
          <table class="service-table">
            <tr>
              <td class="td-servis">01</td>
              <td class="td-servis">Interior Desain</td>
            </tr>
            <tr>
              <td class="td-servis">02</td>
              <td class="td-servis">Consultant</td>
            </tr>
            <tr>
              <td class="td-servis">03</td>
              <td class="td-servis">Construction Consultant</td>
            </tr>
          </table>
        </div>
      </div>
      <img class="service-image" src="../assets/unsplash_vPKNB_gc23Q.png" alt="service image">
    </div>
</template>
<script>
    export default {
        name: 'home service'
    }
</script>

<style>
.home-service {
  margin-top: 160px;
  display: flex;
  flex-direction: column;
  position: relative;
}

.home-service-top {
  width: 883px;
  height: 467px;
  background: #FFFFFF;
  z-index: 1;

}

.font-service-content {
  width: 780px;
  height: 61px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 20px 0 0 0;
}

.font-service-text {
  width: 471px;
  height: 87px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
  margin: 24px 0 0 0;
}

.service-table {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 34px;
  color: #333333;
  margin: 40px 0 0 0;
}

.td-servis {
  padding: 0;
  padding-right: 40px;
  padding-bottom: 33px;
}

.service-image {
  position: absolute;
  z-index: 0;
  align-self: flex-end;
  width: 1076px;
  height: 524.55px;
  top: 304px;

  /* left: 244px; */
}
</style>