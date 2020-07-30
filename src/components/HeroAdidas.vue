<template>
    <div>
       <!-- Hero Section Begin -->
      <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">

            <div class="single-hero-items set-bg" style="background-image: url('/img/adidas.png')">
                <div class="container">
                    <div class="center">
                        <div class="col-lg-5">
                            <span>ADIDAS</span>
                            <h1>INDONESIA</h1>
                            <p>
                                Selamat Datang di store kami!
                            </p>
                            <a href="#" class="primary-btn">Buy Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg" style="background-image: url('/img/white.png')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                           <a href="#" class="primary-btn">Buy Now</a>
                    </div>
                    </div>
                </div>
            </div>
        </carousel>
    </section>
    <!-- Hero Section End -->
    </div>
</template>

<script>
import carousel from "vue-owl-carousel";

    export default {
        name: 'HeroAdidas',
        components: {
            carousel
        }
    }
</script>