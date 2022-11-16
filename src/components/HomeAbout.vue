<template>
    <div class="home-about">
        <div class="home-about-top">
          <p class="home-about-title">ABOUT</p>
          <p class="home-about-content">“We're one of the best furniture agency. Prioritizing customers and making purchases easy are the hallmarks of our agency.”</p>
        </div>
        <div class="home-about-bottom">
          <img class="home-about-image" src="../assets/home2.svg" alt="about image">
          <div class="home-about-account">
              <img class ="account-image" src="../assets/home3.svg" alt="account image">
              <div>
              <p class="font-account-name">Arga Danaan</p>
              <p class="font-account-position">CEO of Dananz</p>
              </div>
          </div>
          <div class="home-about-text">
              <p class="font-about-text">Online learning with us does not interfere with your daily life. because learning can be done anytime and anywhere.</p>
              <button class="btn--home-about">Learn More</button>
          </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'home about'
    }
</script>

<style>
    .home-about {
    margin-top: 160px;
    height: 751px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* background-color: aqua; */
    }
    
    .home-about-top {
      height: 210px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .home-about-title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    margin: 0;
    color: #333333;
    }

  .home-about-content {
    width: 1200px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 61px;
    color: #333333;
    margin: 0 0 0 0;
  }

  .home-about-bottom {
    position: relative;
    display: flex;
    justify-content: space-between;
    width: 1200px;
    margin: 0;
  }

  .home-about-image {
    width: 883px;
    height: 525px;
  }

  .home-about-account {
    /* box-shadow:  0.1px 0.1px #888888; */
    width: 276px;
    height: 90px;
    position: absolute;
    z-index: 2;
    top: 27px;
    left: 808px;
    display: flex;
    align-items: center;
    background-color: #fff;
  }

  .account-image {
    width: 51px;
    height: 56px;
    margin: 0 20px 0 20px;
  }

  .font-account-name {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    line-height: 25px;
    margin: 0;
  }

  .font-account-position {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    color: #9C9C9C;
    margin: 0;
  }

  .home-about-text {
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;

  }

  .font-about-text {
    width: 223px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    color: #9C9C9C;
    margin: 0;
  }

  .btn--home-about {
    width: 142px;
    height: 49px;
    background-color: #2C3878;
    border: 0;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 21px;
    color: #FFFFFF;
    position: absolute;
    bottom: 94px;
  }
</style>