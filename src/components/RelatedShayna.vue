<template>
  <!-- Related Products Section End -->
  <div class="related-products spad">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="section-title">
            <h2>Related Products</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/related-product-1.jpg" alt="" />
              <ul>
                <li class="w-icon active">
                  <a href="#"><i class="icon_bag_alt"></i></a>
                </li>
                <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">Shoes</div>
              <a href="#">
                <h5>Soft Retro Sneakers</h5>
              </a>
              <div class="product-price">
                899,900 IDR
                <span>999,900 IDR</span>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/related-product-2.jpg" alt="" />
              <ul>
                <li class="w-icon active">
                  <a href="#"><i class="icon_bag_alt"></i></a>
                </li>
                <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">T-Shirt</div>
              <a href="#">
                <h5>Bugs Bunny Looney Tunes © &™ Warner Bros T-Shirt</h5>
              </a>
              <div class="product-price">499,900 IDR</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/related-product-3.jpg" alt="" />
              <ul>
                <li class="w-icon active">
                  <a href="#"><i class="icon_bag_alt"></i></a>
                </li>
                <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">T-Shirt</div>
              <a href="#">
                <h5>Skull Print T-Shirt</h5>
              </a>
              <div class="product-price">499,900 IDR</div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 col-sm-6">
          <div class="product-item">
            <div class="pi-pic">
              <img src="img/related-product-4.jpg" alt="" />
              <ul>
                <li class="w-icon active">
                  <a href="#"><i class="icon_bag_alt"></i></a>
                </li>
                <li class="quick-view">
                    <router-link to="/product">+ Quick View</router-link>
                    </li>
              </ul>
            </div>
            <div class="pi-text">
              <div class="catagory-name">T-Shirt</div>
              <a href="#">
                <h5>National Geographic™ Print T-Shirt</h5>
              </a>
              <div class="product-price">499,900 IDR</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Related Products Section End -->
</template>

<script>
export default {
    name: "RelatedShayna",
    components: {

    },
}
</script>