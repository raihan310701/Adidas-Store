<template>
     <div>
        <!-- Partner Logo Section Begin -->
        <div class="partner-logo">
        <div class="container">
            <carousel class="logo-carousel" :loop="true" :autoplay="true" :items="1">
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/adidas.png" alt="" />
                    </div>
                </div>
            </carousel>
        </div>
    </div>
    <!-- Partner Logo Section End -->
     </div>
</template>

<script>
   import carousel from "vue-owl-carousel";

    export default {
        name: 'LogoAdidas',
        components: {
            carousel,
        }
    }
</script>