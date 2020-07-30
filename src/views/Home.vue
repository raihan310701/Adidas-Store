<template>
  <div class="home">
      <HeaderAdidas />
      <FooterAdidas />
      <HeroAdidas />
      <carousel />
      <ProductAdidas />
      <Instagram />
      <LogoAdidas />
      <ProdukLain />
      <carousel />
  </div>
</template>

<script>
    import HeaderAdidas from "@/components/HeaderAdidas.vue";
    import FooterAdidas from "@/components/FooterAdidas.vue";
    import carousel from 'vue-owl-carousel';
    import HeroAdidas from "@/components/HeroAdidas";
    import ProductAdidas from "@/components/ProductAdidas.vue";
    import Instagram from "@/components/Instagram.vue";
    import LogoAdidas from "@/components/LogoAdidas.vue";
    import ProdukLain from "@/components/ProdukLain.vue";

      export default {
          name: "home",
          components: {
              HeaderAdidas,
              FooterAdidas,
              carousel,
              HeroAdidas,
              ProductAdidas,
              Instagram,
              LogoAdidas,
              ProdukLain
          }
      };
</script>