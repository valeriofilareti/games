<script>
import SpecialCategories from './SpecialCategories.vue';
import Products from './Products.vue';

import { Swiper, SwiperSlide } from 'swiper/vue';
  // import Swiper styles
  import 'swiper/css';

export default {
name: 'myMain',
data(){
  return {

  }
},
components: {
  SpecialCategories,
  Products
}


}
</script>

<template>

  <!-- infos --------------------------------------------->
  <div class="container">
    <div class="infos d-flex justify-between">
      <div class="element d-flex">
        <div class="img truck">

        </div>
        <div class="text">
          <span class="truck-txt">Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element d-flex">
        <div class="img bag">
          
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element d-flex">
        <div class="img module">
          
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element d-flex">
        <div class="img hand">
          
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
    </div>
    <!-- infos ----------------------------------------->
    <!-- latest-popular -------------------------------->
    <div class="boxes d-flex justify-between">
      <div class="latest d-flex">
        <div class="text">
          <span class="yellow-box">most popular</span><br>
          <span class="title">The Battlefield 4 Naval Strike</span>
        </div>
      </div>
      <div class="popular d-flex">
        <div class="text">
          <span class="yellow-box">latest game</span><br>
          <span class="title">Assassin's Creed Unity Game</span>
        </div>
      </div>
    </div>
    <!-- latest-popular -------------------------------->
  </div>
  <SpecialCategories /> 
  <Products />
</template>


<style lang="scss" scoped>
@import '../scss/main.scss';

.img {
  width: 65px;
  height: 70px;
  background-image: url(../assets/img/service-icon.png);
  background-position: center -104px;
  background-repeat: no-repeat;
  margin-right: 10px;
}
.img.truck {
  background-position: center -104px;
  transition: .5s;
}
.img.truck:hover {
  background-position: center 7px;
}
.img.bag {
  background-position: center -328px;
  transition: .5s;
}
.img.bag:hover {
  background-position: center -216px;
}
.img.module {
  background-position: center -556px;
  transition: .5s;
}
.img.module:hover {
  background-position: center -445px;
}
.img.hand {
  background-position: center -783px;
  transition: .5s;
}
.img.hand:hover {
  background-position: center -670px;
}
.img.truck {
  background-position: center -104px;
}

.infos {
  margin: 40px 0;
}
span {
  display: inline-block;
}
.latest, .popular {
  width: 48%;
  height: 300px;
  padding: 10px;
  justify-content: flex-end;
  padding-right: 90px;
  padding-top: 30px;
  .text {
    width: 215px;
    line-height: 35px;
    font-weight: 600;
    .yellow-box {
      font-size: 32px;
      padding: 4px 10px;
      font-weight: 600;
      margin-bottom: 8px;
    }
    .title {
      font-size: 39px;
    }
  }
}
.latest {
  background-image: url(../assets/img/cms-banner-01.jpg);
}
.popular {
  background-image: url(../assets/img/cms-banner-02.jpg);
}



</style>