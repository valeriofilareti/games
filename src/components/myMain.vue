<script>
import SpecialCategories from './partials/SpecialCategories';
export default {
name: 'myMain',
data(){
  return {

  }
},
components: {
  SpecialCategories
}

}
</script>

<template>
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
</template>


<style lang="scss" scoped>
@import '../scss/main.scss';
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