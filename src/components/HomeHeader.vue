<template>
    <div class="home-header">
      <div>
        <p  class="home-header-title">Design your interor with high quality.</p>
      </div>
      <div class="home-header-table">
        <div class="table-child">
          <p class="font-number">350+</p>
          <p class="font-text">Project Completed</p>
        </div>
        <div class="table-child">
          <p class="font-number">23+</p>
          <p class="font-text">Professional Teams</p>
        </div>
        <div class="table-child">
          <p class="font-number">15+</p>
          <p class="font-text">Years Experience</p>
        </div>
      </div>
      <div class="home-header-image">
        <img src="../assets/unsplash_G7sE2S4Lab4.png" alt="Home Image">
      </div>
    </div>
</template>

<script>
export default {
    name: 'home header'
}
</script>
<style>
.home-header{
  /* position: absolute; */
  margin-top: 100px;
  margin-inline: auto;
}

.home-header-title {
  width: 681px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 72px;
  line-height: 140%;
  color: #333333;
  margin: 0;
}

.home-header-table {
  width: 252px;
  height: 525px;
  background-color: #2C3878;
  color: #fff ;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  position: absolute;
  z-index: 2;
  top: 331px;
  left: 1046px;
}
 .table-child {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  height: 109px;
 }

.font-number {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 52px;
  line-height: 160%;
  margin: 0;
}
.font-text {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 160%;
  margin: 0;
}

.home-header-image {
  margin-top: 46px;
}
</style>