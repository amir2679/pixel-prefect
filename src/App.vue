
<template>
  <section class="main-layout">
    <app-header />

    <RouterView />
    <app-footer />
  </section>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import appHeader from './cmps/app-header.vue';
import appFooter from './cmps/app-footer.vue';


components: { appHeader, appFooter }
</script>
