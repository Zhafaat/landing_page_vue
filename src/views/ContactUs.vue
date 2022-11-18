<template>
    <div class="contact">
        <ContactHeaderVue/>
        <ContactFormVue/>
        <ContactLocationVue/>

    </div>
</template>

<script>
import ContactHeaderVue from '@/components/Contact/ContactHeader.vue';
import ContactFormVue from '@/components/Contact/ContactForm.vue';
import ContactLocationVue from '@/components/Contact/ContactLocation.vue';
export default {
    name: 'contact us',
    components: {
        ContactHeaderVue,
        ContactFormVue,
        ContactLocationVue
    }

}
</script>

<style>
.contact {
    width: 1200px;
    max-width: 1200px;
    margin-inline: auto;
    display: flex;
    flex-direction: column;
}
</style>