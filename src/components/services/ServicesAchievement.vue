<template>
    <div class="services-achievement">
        <div class="services-achievement-top">
            <p class="services-title">ACHIEVEMENT</p>
        </div>
        <div class="services-achievement-bottom">
            <div class="services-achievement-bottom-left">
                <img class="services-achievement-image" src="../../assets/unsplash_services2.svg" alt="services-achievement-image1">
                <img class="services-achievement-image" src="../../assets/unsplash_services3.svg" alt="services-achievement-image2">
                <img class="services-achievement-image" src="../../assets/unsplash_services4.svg" alt="services-achievement-image3">
            </div>
            <div class="services-achievement-bottom-right">
                <div>
                    <p class="services-achievement-subcontent">Interior design</p>
                    <p class="services-achievement-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
                </div>
                <div>
                    <p class="services-achievement-subcontent">Consultant</p>
                    <p class="services-achievement-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
                </div>
                <div>
                    <p class="services-achievement-subcontent">Construction consultant</p>
                    <p class="services-achievement-text">Customize your interior design into a dream place with the best designers and quality furniture. We try our best to fulfill your expectations.</p>
                </div>
            </div>
        </div> 
    </div>   
</template>

<script>
export default {
    name: 'services achievement'
}
</script>

<style>
.services-achievement {
    margin: 100px 0 0 0;
    height: 1239px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* background-color: aqua; */
}

.services-title {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    color: #000000;
    margin: 0;
}

.services-achievement-bottom {
    margin: 0;
    width: 1200px;
    display: flex;
    justify-content: space-between;
}

.services-achievement-bottom-left {
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 1175px;
}

.services-achievement-image {
    width: 746px;
    height: 365px;
}

.services-achievement-bottom-right {
    width: 334px;
    height: 1034px;
    display: flex;
    flex-direction: column;
    align-self: center;
    justify-content: space-between;
}

.services-achievement-subcontent {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 34px;
    color: #333333;
    margin: 0;
}

.services-achievement-text {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 160%;
    color: #9C9C9C;
    margin: 20px 0 0 0;
}
</style>