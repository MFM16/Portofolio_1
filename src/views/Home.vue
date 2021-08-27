<template>
  <div class="home">
    <Header />
    <Cars />
    <Banner />
    <Instagram />
    <Logo />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Cars from "@/components/Carousel.vue";
import Banner from "@/components/Banner.vue";
import Instagram from "@/components/Instagram.vue";
import Logo from "@/components/Logo.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Cars,
    Banner,
    Instagram,
    Logo,
    Footer
  },
};
</script>
