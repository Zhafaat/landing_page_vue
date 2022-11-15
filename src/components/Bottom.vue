<template>
    <div class="container">
      <div class="background-footer-top">
        <div class="footer-top">
          <p class="font-footer-content">let's discuss making your interior like a dream place!</p>
          <div>
            <p class="font-footer-text">Contact us below to work together to build your amazing interior</p>
            <button class="btn-footer">Contact Us</button>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <div>
          <p class="font-footer-title">Dananz</p>
          <p class="font-bottom-content">One of the best furniture agency.</p>
        </div>
        <div class="footer-bottom-right">
          <ul>
            <li>Enter  your email to get the laterst news</li>
          </ul>
          <p class="font-bottom-text">Email Address</p>
          <div class="footer-sosmed">
            <p class="font-sosmed">Follow us On</p>
            <div class="sosmed-logo">
              <div class="fb-bg">
                <img class="fb" src="../assets/Vectorfb.svg" alt="fb logo">
              </div>
              <div class="ig-bg">
                <img class="ig" src="../assets/ig.svg" alt="ig logo">
              </div>
              <div class="tiktok-bg">
                <img class="tiktok" src="../assets/tiktok.svg" alt="tiktok logo">
              </div>
              <div class="youtube-bg">
                <img class="youtube" src="../assets/youtube.svg" alt="yt logo">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: 'bottom'
    }
</script>

<style>
.container {
  margin: 100px 0 0 0;
  display: flex;
  flex-direction: column;
  max-width: 1440px;
  height: 598px;
  /* background-color: darkgray; */
}

.background-footer-top {
  width: 1440px;
  height: 203px;
  background-color: #2C3878; 
  display: flex;
  justify-content: center;
  /* align-items: center; */
}

.footer-top {
  width: 1200px;
  display: flex;
  align-items:center;
  justify-content: space-between;
}

.font-footer-content {
  width: 613px;
  height: 122px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #FFFFFF;
  margin: 0;
}

.font-footer-text {
  width: 432px;
  height: 58px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #D9D9D9;
  margin: 0;
}

.btn-footer {
  width: 142px;
  height: 49px;
  background: #FFFFFF;
  margin: 20px 0 0 0;
  border: 0;

  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  color: #333333;
}

.footer-bottom {
  align-self: center;
  width: 1200px;
  max-width: 1200px;
  display: flex;
  justify-content: space-between;
  margin: 80px 0 0 0;
  /* background-color: aqua; */
}

.font-footer-title {
  /* width: 126px;
  height: 54px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 31.9301px;
  line-height: 54px;
  color: #000000;
  margin: 0;
}

.font-bottom-content {
  width: 481px;
  /* height: 122px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 36px;
  line-height: 61px;
  color: #333333;
  margin: 10px 0 0 0;
}

.footer-bottom-right {
  width: 440px;
  margin: 32px 0 0 0;
  display: flex;
  flex-direction: column;
}

ul {
  margin: 0;
  padding: 0 0 0 20px;
}

li {
  width: 356px;
  /* height: 29px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 29px;
  color: #333333;
}

.font-bottom-text {
  width: 113px;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 26px;
  color: #D9D9D9;
  margin: 23.23px 0 0 0;
}

.footer-sosmed {
  margin: 54.74px 0 0 0;
  width: 203px;
  align-self: flex-end;
  /* background-color:brown; */
}

.font-sosmed {
  width: 100px;
  /* height: 26px; */
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 26px;
  color: #333333;
  margin: 0;
}

.sosmed-logo {
width: 203px;
display: flex;
justify-content: space-between;
align-items: center;
margin: 10px 0 0 0;
}

.fb-bg {
  width: 32px;
  height: 32px;
  /* position: relative; */
  border-radius: 50%;
  background: #D9D9D9;
  display: flex;
  justify-content: center;
  align-items: center;
}

.fb {
  width: 20px;
  height: 20px;
}

.ig-bg {
  width: 32px;
  height: 32px;
  /* position: relative; */
  border-radius: 50%;
  background: #D9D9D9;
  display: flex;
  justify-content: center;
  align-items: center;

}
.ig {
  width: 30px;
  height: 30px;
  /* position: absolute; */
}

.tiktok-bg {
  width: 32px;
  height: 32px;
  /* position: relative; */
  border-radius: 50%;
  background: #D9D9D9;
  display: flex;
  justify-content: center;
  align-items: center;
}

.tiktok {
  width: 17.44px;
  height: 20px;
}

.youtube-bg {
  width: 32px;
  height: 32px;
  /* position: relative; */
  border-radius: 50%;
  background: #D9D9D9;
  display: flex;
  justify-content: center;
  align-items: center;
}

.youtube {
  width: 20px;
  height: 14.02px;
}
</style>