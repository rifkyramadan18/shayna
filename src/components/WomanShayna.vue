<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel
            class="product-slider"
            :items="3"
            :nav="false"
            :autoplay="true"
            :dots="false"
            :loop="true"
          >
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/z_tshirt.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    <!-- <a href="product.html">+ Quick View</a> -->
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">T-Shirt</div>
                <a href="#">
                  <h5>FACE PRINT T-SHIRT</h5>
                </a>
                <div class="product-price">
                  499,900 IDR
                  <span>699,900 IDR</span>
                </div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/z_shirt.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    <!-- <a href="#">+ Quick View</a> -->
                    </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Shirt</div>
                <a href="#">
                  <h5>TEXTURED CHECK SHIRT</h5>
                </a>
                <div class="product-price">729,900 IDR</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/z_pant.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    <!-- <a href="#">+ Quick View</a> -->
                    </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Pant</div>
                <a href="#">
                  <h5>
                    LINEN - COTTON <br />
                    BERMUDA SHORTS
                  </h5>
                </a>
                <div class="product-price">629,900 IDR</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/z_blazzer.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <a href="#"><i class="icon_bag_alt"></i></a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    <!-- <a href="#">+ Quick View</a> -->
                    </li>
                  <li class="w-icon">
                    <a href="#"><i class="fa fa-random"></i></a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Blazzer</div>
                <a href="#">
                  <h5>
                    COMFORT FIT WOOL <br />
                    BLEND BLAZER
                  </h5>
                </a>
                <div class="product-price">1,999,900 IDR</div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";
export default {
  name: "WomanShayna",
  components: {
    carousel,
  },
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
</style>