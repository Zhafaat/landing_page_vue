<template>
    <form class="contact-form" action="">
        <div class="contact-form-data">
            <div class="contact-form-name">
                <div class="contact-form-name-box">
                    <p class="form-label">First Name</p>
                    <input class="input-name-box" type="text" placeholder="First Name">
                </div>
                <div class="contact-form-name-box">
                    <p class="form-label">Last Name</p>
                    <input class="input-name-box" type="text" placeholder="Last Name">
                </div>
            </div>
            <div class="contact-form-email">
                <p class="form-label">Email</p>
                <input class="input-email-box" type="text" placeholder="Email">
            </div>
            <div class="contact-form-phoneNumber">
                <p class="form-label">Phone Number</p>
                <div class="input-phoneNumber-box">
                    <p class="country form-label">US</p>
                    <img class="arrow" src="../../assets/arrow.svg" alt="arrow">
                    <input class="phoneNumber" type="text" placeholder="First Name">
                </div>
            </div>
            <div class="contact-form-message">
                <p class="form-label">Message</p>
                <textarea class="input-message-box" name="" id="" placeholder="Your Message"></textarea>
            </div>
        </div>
        <button class="contact-form-submit" type="submit">Send Massage</button>
    </form>
</template>

<script>
    export default {
        name: 'contact form'
    }
</script>

<style>
.contact-form {
    margin: 51px 0 0 0;
    height: 657px;
    width: 840px;
    /* margin-inline: auto; */
    align-self: center;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* background-color: aqua; */
}

.contact-form-data {
    width: 840px;
    height: 568px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    /* background-color: aquamarine; */
}

.contact-form-name {
    width: 840px;
    display: flex;
    justify-content: space-between;
}

.contact-form-name-box {
    height: 99px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.form-label {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    color: #333333;
    margin: 0;
    /* padding-left: 32px; */
}

.input-name-box {
    box-sizing: border-box;
    width: 413px;
    height: 62px;
    background: #FFFFFF;
    border: 1px solid #9C9C9C;
    padding-left: 32px;

    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #333333;
}

.contact-form-email {
    height: 99px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.input-email-box {
    box-sizing: border-box;
    width: 840px;
    height: 62px;
    background: #FFFFFF;
    border: 1px solid #9C9C9C;
    padding-left: 32px;

    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #333333;
}

.contact-form-phoneNumber {
    height: 99px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.input-phoneNumber-box {
    box-sizing: border-box;
    width: 840px;
    height: 62px;
    background: #FFFFFF;
    border: 1px solid #9C9C9C;
    display: flex;
    align-items: center;

}

.country {
    margin-left: 32px;
}

.arrow {
    width: 14px;
    height: 7px;
    margin: 0 0 0 5px;

}

.phoneNumber {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #333333;
    border: none;
    margin-left: 29px;
}

.contact-form-message {
    height: 214px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.input-message-box {
    box-sizing: border-box;
    width: 839px;
    height: 178px;
    background: #FFFFFF;
    border: 1px solid #9C9C9C;
    padding: 20px 30px 20px 30px;

    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #333333;
}

.contact-form-submit {
    box-sizing: border-box;
    width: 168px;
    height: 49px;
    background: #2C3878;
    border: 1px solid #3C3C3C;
    align-self: center;

    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 21px;
    color: #FFFFFF;
}

</style>
