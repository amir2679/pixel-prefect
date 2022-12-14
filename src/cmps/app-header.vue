<template>
    <section class="app-header">
        <div class="header-logo">
            <img src="../assets/images/logo.svg" alt="">
        </div>
        <header-nav/>
    </section>
</template>

<script>
import headerNav from './header-nav.vue';
    export default {
        components: {headerNav}
    }
</script>
