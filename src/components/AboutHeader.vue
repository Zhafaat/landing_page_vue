<template>
    <div class="about-header">
      <p class="about-header-title font-700">About</p>
      <p class="about-header-text font-400">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
      <img class="about-header-image" src="../assets/unsplash_about1.svg" alt="about image">
    </div>
</template>

<script>
    export default {
        name: 'about header'
    }
</script>

<style>
.about-header {
  height: 771;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  margin: 100px 0 0 0;
}

.about-header-title {
  font-size: 56px;
  line-height: 78px;
  color: #000000;
}

.about-header-text {
  width: 582px;
  font-size: 18px;
  line-height: 29px;
  text-align: center;
  color: #000000;
  margin-top: 36px;
}

.about-header-image {
  width: 1200px;
  height: 513px;
  margin: 86px 0 0 0;
}
</style>