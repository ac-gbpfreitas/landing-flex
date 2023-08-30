<template>
  <HeroBanner />
  <MainContent />
  <FooterComponent />
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeroBanner from './components/HeroBanner.vue';
import MainContent from './components/MainContent.vue';

export default {
  name: 'App',
  components: {
    HeroBanner,
    FooterComponent,
    MainContent
  }
}
</script>

<style>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css");
@import url("./assets/css/style.min.css");
</style>
