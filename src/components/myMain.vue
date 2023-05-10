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

<!-- <swiper
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
  </swiper> -->


  <!-- infos --------------------------------------------->
  <div class="container">
    <div class="infos d-flex justify-between">
      <div class="element d-flex">
        <div class="img truck">

        </div>
        <div class="text">
          <span>Free Delivery</span>
          <span>Free Shipping On All Order</span>
        </div>
      </div>
      <div class="elemen d-flex">
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
}
.img.bag {
  background-position: center -328px;
}
.img.module {
  background-position: center -556px;
}
.img.hand {
  background-position: center -783px;
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
  border: 1px solid white;
  padding: 10px;
  justify-content: flex-end;
  padding-right: 90px;
  padding-top: 30px;
  .text {
    width: 215px;
    .yellow-box {
      font-size: 28px;
      padding: 0 8px;
      font-weight: 600;
    }
    .title {
      font-size: 34px;
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