<template>
    <div class="home-material">
      <div class="home-material-left">
        <p class="home-material-title">MATERIAL</p>
        <p class="home-material-content">choice of materials for quality furniture.</p>
        <p class="home-material-text">You can custom the material as desired. And our furniture uses the best materials and selected quality materials.</p>
        <button class="btn-material">See Materials</button>
      </div>
      <div class="home-material-right">
        <img class="material-image1" src="../assets/unsplash_WItJTJsW97w.png" alt="marial image">
        <img class="material-image2" src="../assets/unsplash_Q3stHYxwJWM.png" alt="material image">
        <img class="material-image3" src="../assets/image2.png" alt="material image">
      </div>
    </div>
</template>

<script>
    export default {
        name: 'home material'
    }
</script>

<style>
.home-material {
  margin: 163px 0 20px 0;
  width: 1200px;
  height: 490px;
  display: flex;
  justify-content: space-between;
  /* background-color: aqua; */
}

.home-material-left {
  margin: 0;
  height: 396px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  /* background-color: aliceblue; */
  align-self: center;
}

.home-material-title {
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  margin: 0;
  color: #333333;
}

.home-material-content {
  width: 348px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 0 0 0 0;
}

.home-material-text {
  width: 497px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #9C9C9C;
}

.btn-material {
  width: 159px;
  height: 49px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  color: #333333;
  background-color: #fff;
  border: 1px solid #3C3C3C;
}

.home-material-right {
  position:relative;
  width: 623px;
  height: 490px;
  /* background-color:aquamarine; */
}

.material-image1 {
  position: absolute;
  width: 194.97px;
  height: 178px;
  left: 381.84px;
  top: 265px;
}
.material-image2 {
  position: absolute;
  width: 241px;
  height: 225px;
  left: 381.84px;
  top: 0px;
}
.material-image3 {
  position: absolute;
  width: 341.84px;
  height: 392px;
  left: 0px;
  top: 98px;
}
</style>