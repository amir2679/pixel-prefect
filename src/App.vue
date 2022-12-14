
<template>
  <section class="main-layout">
    <app-header />

    <RouterView />
  </section>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import appHeader from './cmps/app-header.vue';


components: { appHeader }
</script>
