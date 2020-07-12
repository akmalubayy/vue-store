<template>
  <div class="home">
    <Header />
    <Hero />
    <HeroProduk />
    <InstaGallery />
    <Partners />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import HeroProduk from '@/components/HeroProduk.vue';
import InstaGallery from '@/components/InstaGallery.vue';
import Partners from '@/components/Partners.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    HeroProduk,
    InstaGallery,
    Partners,
    Footer,
  },
};
</script>
