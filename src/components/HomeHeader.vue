<template>
    <div class="home-header">
      <p  class="home-header-title">Design your interor with high quality.</p>
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
      <img class="home-header-image" src="../assets/home1.svg" alt="Home Image">
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
  height: 862px;
  margin: 100px 0 0 0;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  /* background-color: aqua; */
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
  bottom: 197px;
  left: 806px;
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
  width: 1200px;
  height: 513px;
}
</style>