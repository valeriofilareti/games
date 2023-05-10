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
  Products,
  Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
      onSlideChange,
    };
  }

}
</script>

<template>

<swiper
    :slides-per-view="3"
    :space-between="50"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide>Slide 1</swiper-slide>
    <swiper-slide>Slide 2</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
    <swiper-slide>Slide 3</swiper-slide>
  </swiper>


  <!-- infos --------------------------------------------->
  <div class="container">
    <div class="infos d-flex justify-between">
      <div class="element d-flex">
        <div class="img">
          <img src="../assets/img/truck.png" alt="">
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="elemen d-flex">
        <div class="img">
          <img src="../assets/img/truck.png" alt="">
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element d-flex">
        <div class="img">
          <img src="../assets/img/truck.png" alt="">
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element d-flex">
        <div class="img">
          <img src="../assets/img/truck.png" alt="">
        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="element"></div>
      <div class="element"></div>
      <div class="element"></div>
    </div>
    <!-- infos ----------------------------------------->
    <!-- latest-popular -------------------------------->
    <div class="boxes d-flex justify-between">
      <div class="latest">
        <div class="text">
          <span class="yellow-box">most popular</span>
          <span>battlefield</span>
        </div>
      </div>
      <div class="popular">
        <div class="text">
          <span class="yellow-box">latest game</span>
          <span>assassins</span>
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

// @import 'swiper/css';

span {
  display: inline-block;
}
.latest, .popular {
  width: 48%;
  height: 300px;
  border: 1px solid white;
  padding: 10px;
}
.latest {
  background-image: url(../assets/img/cms-banner-01.jpg);
}
.popular {
  background-image: url(../assets/img/cms-banner-02.jpg);
}



</style>