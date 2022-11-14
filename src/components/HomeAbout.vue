<template>
    <div class="home-about">
        <div class="home-about-top">
            <div>
            <p class="font-subcontent">ABOUT</p>
            </div>
            <p class="font-about-content">“We're one of the best furniture agency. Prioritizing customers and making purchases easy are the hallmarks of our agency.”</p>
        </div>
        <div class="home-about-bottom">
            <div class="home-about-bottom-absolute">
            <img class="about-image" src="../assets/unsplash_NvqYkDPE0Rw.png" alt="about image">
            <div class="about-account">
                <img class ="account-image" src="../assets/Ellipse332.png" alt="account image">
                <div>
                <p class="font-account-name">Arga Danaan</p>
                <p class="font-account-position">CEO of Dananz</p>
                </div>
            </div>
            <div class="about-text">
                <p class="font-about-text">Online learning with us does not interfere with your daily life. because learning can be done anytime and anywhere.</p>
                <button class="btn--home-about">Learn More</button>
            </div>
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
    display: flex;
    flex-direction: column;
    }
    .font-subcontent {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    margin: 0;
    color: #333333;
    }

  .font-about-content {
    width: 1200px;
    height: 122px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 61px;
    /* or 61px */
    color: #333333;
    margin: 20px 0 0 0;
  }

  /* .home-about-bottom {
    position: absolute;
  } */

  .home-about-bottom-absolute {
    position: relative;
    display: flex;
    justify-content: space-between;
    width: 1200px;
    margin: 60px 0 0 0;
  }



  .about-image {
    width: 883px;
    height: 525px;
  }

  .about-account {
    box-shadow:  0.1px 0.1px #888888;
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
    line-height: 140%;
    margin: 0;
  }

  .font-account-position {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 160%;
    color: #9C9C9C;
    margin: 0;
  }

  .font-about-text {
    width: 223px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 29px;
    color: #9C9C9C;
    margin: 197px 0 40px 0;
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
  }
</style>