<template>
  <section class="home-page">
    <div class="main-content">
      <img src="../assets/images/illustration-intro.png" alt="" class="main-img">
      <div class="overview">
        All your files in one secure location, accessible anywhere.
      </div>
      <pre class="summery">
        Fylo stores all your most important files in one secure location.
        Access them wherever you need, share and collaborate with 
        friends family, and co-workers.
      </pre>
      <button>Get started</button>
      <!-- <div class="btn start-btn"><div>Get started</div></div> -->

      <home-page-overview/>
      <home-page-more/>
      <reviews-preview/>
      <contact-form/>
    </div>
  </section>
</template>

<script>

import homePageOverview from '../cmps/home-page-overview.vue'
import homePageMore from '../cmps/home-page-more.vue';
import reviewsPreview from '../cmps/reviews-preview.vue';
import contactForm from '../cmps/contact-form.vue'
  export default {
    components: {homePageOverview , homePageMore , reviewsPreview , contactForm}
  }
</script>
