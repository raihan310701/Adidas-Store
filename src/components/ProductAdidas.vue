<template>
    <div>
    <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <carousel class="product-slider" items="3" :nav="false" autoplay="true">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/grey.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view">
                                      <a href="#">+ Lihat Barang</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">SHOES</div>
                                <router-link to="/product">
                                   <a href="#">
                                    <h5>Ultraboost 20 Grey</h5>
                                   </a>
                                </router-link>
                                <div class="product-price">
                                    Rp. 750.000
                                    <span>Rp. 1.500.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Meriam.jpeg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Lihat Barang</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Jersey</div>
                                <a href="#">
                                    <h5>Arsenal 2020/21 | HOME</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 3.000.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/bayern.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Lihat Barang</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Jersey Football</div>
                                <a href="#">
                                    <h5>Bayern Muenchen 20/21 | AWAY</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 4.000.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Predator.jpeg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view">
                                      <router-link to="/product">+Lihat Barang</router-link>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">SHOES FOOTBALL</div>
                                <a href="#">
                                    <h5>PREDATOR 20</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 25.000.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Yeezy.jpeg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Lihat Barang</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Slippers</div>
                                <a href="#">
                                    <h5>YEEZY SLIDE BONE</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 30.000.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/Alpha.jpeg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Lihat Barang</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">SNICKERS</div>
                                <a href="#">
                                    <h5>ALPHA EDGE</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 5.000.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/muenchen.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Lihat Barang</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Jersey Football</div>
                                <a href="#">
                                    <h5>Bayern Muenchen | HOME</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 4.500.000
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->
    </div>
</template>

<script>
import carousel from "vue-owl-carousel";
      export default {
          name: 'ProductAdidas',
          components: {
              carousel,
          }
      };
</script>

<style scoped>
     .product-item {
         margin-right: 50px;
     }
</style>