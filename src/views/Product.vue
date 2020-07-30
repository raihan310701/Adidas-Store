<template>
  <div class="product">
      <HeaderAdidas />
            <!-- Breadcrumb Section Begin -->
            <div class="breacrumb-section text-left">
             <div class="container">
               <div class="row">
                <div class="col-lg-12">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
                        <span>Detail</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <section class="product-shop spad page-details">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="row">
                        <div class="col-lg-6">
                            <div class="product-pic-zoom">
                                <img class="product-big-img" :src="Predator" alt="" />
                            </div>
                            <div class="product-thumbs">
                                <carousel :dots="false" :nav="false" class="product-thumbs-track ps-slider">
                                    <div class="pt active" @click="changeImage(thumbs[0])" :class="thumbs[0] == Predator ? 'active' : '' ">
                                        <img src="img/Predator.jpeg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[1])" :class="thumbs[1] == Dator ? 'active' : '' ">
                                        <img src="img/Dator.jpg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[2])" :class="thumbs[2] == mutator ? 'active' : '' ">
                                        <img src="img/mutator.jpg" alt="" />
                                    </div>

                                    <div class="pt" @click="changeImage(thumbs[3])" :class="thumbs[3] == black ? 'active' : '' ">
                                        <img src="img/black.jpg" alt="" />
                                    </div>
                                </carousel>
                            </div>
                        </div>
                        <div class="col-lg-6">
                            <div class="product-details text-left">
                                <div class="pd-title">
                                    <span>ADIDAS</span>
                                    <h3>PREDATOR 20</h3>
                                </div>
                                <div class="pd-desc">
                                    <p>
                                       Predator 20 secara eksklusif tersedia sekarang melalui toko-toko adidas Pacific Place, Senayan City, Central Park, Pondok Indah Mall dan mitra ritel terpilih.
                                    </p>
                                    <h4>Rp. 25.000.000</h4>
                                </div>
                                <div class="quantity">
                                    <router-link to="/card"><a href="shopping-cart.html" class="primary-btn pd-cart">Beli Sekarang</a></router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Product Shop Section End -->
      <ProdukLain />

      <FooterAdidas />
  </div>
</template>

<script>
    import HeaderAdidas from "@/components/HeaderAdidas.vue";
    import FooterAdidas from "@/components/FooterAdidas.vue";
    import ProdukLain from "@/components/ProdukLain.vue";

    import carousel from "vue-owl-carousel";

      export default {
          name: "product",
          components: {
              HeaderAdidas,
              FooterAdidas,
              ProdukLain,
              carousel
          },
          data() {
              return {
                  Predator: "img/Predator.jpeg",
                thumbs: [
                    "img/Predator.jpeg",
                    "img/Dator.jpg",
                    "img/mutator.jpg",
                    "img/black.jpg",
                ]
              }
          },
          methods: {
              changeImage(urlImage) {
                  this.Predator = urlImage;
              }
          }
      };
</script>

<style scoped>
     .product-thumbs .pt {
         margin-right: 14px;
     }
</style>