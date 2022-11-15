<template>
    <div class="about-achievement">
      <div class="about-achievement-top">
        <p class="about-achievement-title font-500">ACHIEVEMENT</p>  
        <p class="about-achievement-content font-600">interior customization with Danaanz, best quality with professional workers</p>
      </div>
      <div class="about-achievement-bottom">
        <img src="../assets/unsplash_about2.svg" alt="achievement image">
        <div class="about-achievement-table">
          <div class="flex-center">
            <p class="table-number font-400">350+</p>
            <p class="table-text font-400">Project Completed</p>
          </div>
          <div class="flex-center">
            <p class="table-number font-400">23+</p>
            <p class="table-text font-400">Professional Teams</p>
          </div>
          <div class="flex-center">
            <p class="table-number font-400">15+</p>
            <p class="table-text font-400">Years Experience</p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'about achievement'
}
</script>

<style>
.about-achievement {
  /* width: 1200px; */
  height: 747px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin: 100px 0 0 0;
  /* background-color: aqua; */
}

.about-achievement-title {
  font-size: 16px;
  line-height: 24px;
  color: #000000;
}

.about-achievement-content {
  width: 738px;
  font-size: 36px;
  line-height: 61px;
  color: #000000;
  margin-top: 20px;
}

.about-achievement-bottom {
  display: flex;
  justify-content: space-between;
  margin: 56px 0 0 0;
}

.about-achievement-image {
  width: 883px;
  height: 525px;
}

.about-achievement-table {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  width: 252px;
  height: 525px;
  background: #2C3878;
}

.flex-center {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.table-number {
  font-size: 52px;
  line-height: 83px;
  color: #FFFFFF;
}

.table-text {
  font-size: 16px;
  line-height: 26px;
  color: #FFFFFF;
}
</style>