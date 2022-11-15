<template>
    <div class="about-service">
      <div class="about-service-top">
        <p class="about-service-title font-500" >SERVICE</p>
        <p class="about-service-content font-600">Why Choose Us</p>
        <p class="about-service-text font-400">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
      </div>
      <div class="about-service-bottom">
        <div class="about-service-box">
          <img class="about-service-image" src="../assets/Ellipse333.svg" alt="gray circle">
          <p class="box-title font-600">High Quality</p>
          <p class="box-text font-400">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        </div>
        <div class="about-service-box">
          <img class="about-service-image" src="../assets/Ellipse333.svg" alt="gray circle">
          <p class="box-title font-600">Professional Designer</p>
          <p class="box-text font-400">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        </div>
        <div class="about-service-box">
          <img class="about-service-image" src="../assets/Ellipse333.svg" alt="gray circle">
          <p class="box-title font-600">The Best Services</p>
          <p class="box-text font-400">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: 'about service'
    }
</script>

<style>
.about-service {
  margin: 100px 0 0 0;
  height: 552px;
  /* width: 1200px; */
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  /* background-color: aqua; */
}

.about-service-title {
  font-size: 16px;
  line-height: 24px;
  color: #000000;
}

.about-service-content {
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin-top: 20px;
}

.about-service-text {
  width: 471px;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
  margin-top: 25px;
}

.about-service-bottom {
  margin: 40px 0 0 0;
  width: 1200px;
  display: flex;
  justify-content: space-between;
}

.about-service-box {
  width: 388px;
  height: 295px;
  background: #FFFFFF;
  box-shadow: 0px 0px 5px 1px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.about-service-image {
  width: 63px;
  height: 63px;
}

.box-title {
  font-size: 24px;
  line-height: 34px;
  color: #333333;
}

.box-text {
  /* width: 334px; */
  font-size: 18px;
  line-height: 29px;
  text-align: center;
  color: #9C9C9C;
}
</style>