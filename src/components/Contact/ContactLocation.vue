<template>
    <div class="contact-location">
        <p class="contact-location-title">Location</p>
        <div class="contact-location-content-bg">
            <div class="contact-location-left">
                <p class="contact-location-content">Visit Our Stores</p>
                <p class="contact-location-text">Find us at these locations.</p>
                <div class="contact-location-email-phone">
                    <ContactLocationEmailPhoneVue media="Email" adress="dananz@gmail.com" />
                    <ContactLocationEmailPhoneVue media="Phone" adress="+62 815 002 1000" />
                </div>
            </div>
            <div class="contact-location-right">
                <div class="contact-location-right-city">
                    <ContactLocationCityVue cityName="Jakarta" />
                    <ContactLocationCityVue cityName="Surakarta" />
                </div>
                <div class="contact-location-right-city">
                    <ContactLocationCityVue cityName="Yogyakarta" />
                    <ContactLocationCityVue cityName="Bandung" />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import ContactLocationCityVue from './ContactLocationCity.vue';
    import ContactLocationEmailPhoneVue from './ContactLocationEmailPhone.vue';
    export default {
        name: 'contact location',
        components: {
            ContactLocationCityVue,
            ContactLocationEmailPhoneVue
        }
    }
</script>

<style>
    .contact-location {
        height: 445px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        /* background-color: aqua; */
        margin: 100px 0 1px 0;
    }

    .contact-location-title {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 24px;
        color: #000000;
        margin: 0;
    }

    .contact-location-content-bg {
        height: 401px;
        display: flex;
        justify-content: space-between;
    }

    .contact-location-left {
        height: 332px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    
    .contact-location-content {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 36px;
        line-height: 61px;
        color: #333333;
        margin: 0;
    }

    .contact-location-text {
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 29px;
        color: #9C9C9C;
        margin: 0;
    }

    .contact-location-email-phone {
        height: 179px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .contact-location-right {
        height: 401px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .contact-location-right-city {
        width: 728px;
        display: flex;
        justify-content: space-between;
    }
</style>