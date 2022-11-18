<template>
    <nav>
      <div class="nav-left">
        <p class="nav-left-title">Dananz</p>
      </div>
      <div class="nav-rigth">
        <div class="navbar">
          <router-link class="link" to="/">Home</router-link>
          <router-link class="link" to="/about">About Us</router-link>
          <router-link class="link" to="/services">Services</router-link>
          <router-link class="link" to="/team">Our Team</router-link>
        </div>
        <div class="contactUs">
          <button class="btn-contact"><router-link class="btn-text" to="/contact">Contact Us</router-link></button>
        </div>
      </div>
    </nav>
</template>

<script>
    export default {
        name: 'navbar'
    }
</script>
<style>
nav {
  margin-inline:auto;
  width: 1200px;
  max-width: 1200px;
  display: flex;
  /* background-color: aqua; */
  justify-content: space-between;
  font-family: 'Poppins', sans-serif;
  margin-top: 42px;
}


.nav-left-title {
  font-size: 31.93px;
  font-weight: 700;
  margin: 0;
  /* background-color: red; */
}

.nav-rigth {
  /* width: 49.58%; */
  display: flex;
  gap: 74px;
  /* background-color:aqua; */

}

.navbar {
  width: 498px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.contactUs {
  display: flex;
  align-items: center;
  font-size: 14px;
}

.btn-contact {
  background-color: #2C3878;
  width: 142px;
  height: 49px;
  border: 0;
}

.btn-text {
  color: #fff;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  text-decoration: none;
}
 
.link {
  text-decoration: none;
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 22px;
  color: #333333;
  margin: 0;
}
</style>