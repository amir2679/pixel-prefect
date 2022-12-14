<template>
    <section class="app-footer">
        <div class="header-logo">
            <img src="../assets/images/logo.svg" alt="">
        </div>

        <div class="about-us-info">
            <div class="location-info">
                <img src="../assets/images/icon-location.svg" alt="">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore
                    et
                    dolore magna aliqua</p>
            </div>
            <div class="contact-us-info">
                <div class="phone">
                    <img src="../assets/images/icon-phone.svg" alt="">
                    <span>+1-543-123-4567</span>
                </div>
                <div class="email">
                    <img src="../assets/images/icon-email.svg" alt="">
                    <span>example@fylo.com</span>
                </div>
            </div>
            <div class="footer-links">
                <span v-for="link in footerLinks">{{ link.txt }}</span>
            </div>

            <div class="social-links">
                <span v-for="socialLink in socialLinks">
                    <i :class="socialLink.class"></i>
                </span>
            </div>
        </div>
    </section>
</template>

<script>
import contactForm from './contact-form.vue';
export default {
    data() {
        return {
            footerLinks: [{ txt: 'About Us', url: '' }, { txt: 'Contact Us', url: '' }, { txt: 'Jobs', url: '' }, { txt: 'Terms', url: '' },
            { txt: 'Press', url: '' }, { txt: 'Privacy', url: '' },
            { txt: 'Blog', url: '' },],

            socialLinks: [{ class: 'fa-brands fa-facebook-f', url: '' },
            { class: 'fa-brands fa-twitter', url: '' },
            { class: 'fa-brands fa-instagram', url: '' }]
        }
    },
    components: {
        contactForm
    }
}
</script>