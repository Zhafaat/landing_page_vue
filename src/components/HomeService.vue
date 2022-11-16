<template>
    <div class="home-service">
      <div class="home-service-top">
        <p class="home-service-title">SERVICE</p>
        <div class="home-service-top-content">
          <p class="home-service-content">attractive furniture with the best quality.</p>
          <p class="home-service-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
          <div class="home-service-top-list">
            <HomeServiceListVue number="01" text="Interior Design"/>
            <HomeServiceListVue number="02" text="Consultant"/>
            <HomeServiceListVue number="03" text="Construction Consultant"/>
          </div>
        </div>
      </div>
      <img class="service-image" src="../assets/unsplash_vPKNB_gc23Q.png" alt="service image">
    </div>
</template>
<script>
    import HomeServiceListVue from './HomeServiceList.vue';
    export default {
        name: 'home service',
        components: {
          HomeServiceListVue
        }
    }
</script>

<style>
.home-service {
  margin-top: 160px;
  height: 828.55px;
  display: flex;
  flex-direction: column;
  position: relative;
  /* background-color: aqua; */
}

.home-service-top {
  width: 883px;
  height: 467px;
  background: #FFFFFF;
  z-index: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.home-service-top-content {
  height: 443px;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.home-service-title {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  margin: 0;
  color: #333333;
}

.home-service-content {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 0;
}

.home-service-text {
  width: 471px;
  height: 87px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
  margin: 0;
}

.home-service-top-list {
  height: 170px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
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