<script>
export default {
  
}

</script>

<template>
  <!-- PERCHE SECTION TITLE IN GENERAL LO RENDE IMMENSO?? -->
  <div class="title d-flex">
    <h1>Our Products</h1>
  </div>
  <div class="container d-flex">


  <div class="card">
    <div class="img">
      <img src="../assets/img/01-300x300.jpg" alt="">
      <img class="hover-img" src="../assets/img/05-300x300.jpg" alt="">
    </div>
    <div class="infos">
      <div class="stars">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
      </div>
      <div class="name">
        <span>Shopping Mahjong Connect</span>
      </div>
      <div class="price">
        <span>£100.00</span>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="img">
      <img src="../assets/img/02-300x300.jpg" alt="">
      <img class="hover-img" src="../assets/img/06-300x300.jpg" alt="">
    </div>
    <div class="infos">
      <div class="stars">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
      </div>
      <div class="name">
        <span>Shopping Mahjong Connect</span>
      </div>
      <div class="price">
        <span>£100.00</span>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="img">
      <img src="../assets/img/03-300x300.jpg" alt="">
      <img class="hover-img" src="../assets/img/07-300x300.jpg" alt="">
    </div>
    <div class="infos">
      <div class="stars">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
      </div>
      <div class="name">
        <span>Shopping Mahjong Connect</span>
      </div>
      <div class="price">
        <span>£100.00</span>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="img">
      <img src="../assets/img/04-300x300.jpg" alt="">
      <img class="hover-img" src="../assets/img/08-300x300.jpg" alt="">
    </div>
    <div class="infos">
      <div class="stars">
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
        <i class="fa-solid fa-star"></i>
      </div>
      <div class="name">
        <span>Shopping Mahjong Connect</span>
      </div>
      <div class="price">
        <span>£100.00</span>
      </div>
    </div>
  </div>

</div>
</template>


<style lang="scss" scoped>
@import '../scss/general/vars';
.title {
  justify-content: center;
  margin-top: 100px;
  font-size: 25px;
  margin-bottom: 45px;
}
img {
  width: 100%;
}
.hover-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 20px;
  display: none;
}
.card:hover .hover-img {
  display: block;
}
.card {
  width: 25%;
  padding: 20px;
  position: relative;
  .infos {
    background-color: #170f1f ;
    padding: 10px;
    div {
      margin: 5px 0;
    }
  }
}
i {
  color: $secondary-color;
}
.price {
  span{
    color: $secondary-color;
  }
}

</style>