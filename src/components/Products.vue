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
        <div class="d-none-options d-flex">
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
        </div>
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
        <div class="d-none-options d-flex">
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
        </div>
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
        <div class="d-none-options d-flex">
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
        </div>
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
        <div class="d-none-options d-flex">
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
          <div class="option"><i class="fa-regular fa-heart"></i></div>
        </div>
      </div>
    </div>
  </div>
</div>
  <!-- games ----------------------------------------------------------------------- -->
  <div class="container">
    <div class="boxes d-flex justify-between">
      <div class="latest d-flex">
        <div class="text">
          <div class="yellow-box">20% Discount</div><br>
          
          <span class="title">Dragon’s Dogma Video Game</span>
        </div>
      </div>
      <div class="popular d-flex">
        <div class="text">
          <div class="yellow-box">30% Discount</div><br>
          <span class="title">World Of Tanks New Game</span>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
@import '../scss/general/vars';

// title-----------------------------------------------------------
.title {
  justify-content: center;
  margin-top: 100px;
  font-size: 25px;
  margin-bottom: 45px;
  position: relative;
}
.title ::after {
  content: '';
  display: block;
  width: 50px;
  height: 2px;
  background-color: $secondary-color;
  text-align: center;
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
}
// title-----------------------------------------------------------
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
.card:hover .d-none-options {
  display: flex;
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
.d-none-options {
  width: 100%;
  height: 30px;
  border-top: 1px solid gray;
  background-color: #170f1f ;
  position: absolute;
  top: 0;
  justify-content: space-around;
  align-items: center;
  display: none;
  i {
    color: white;
  }
  i:hover {
    color: $secondary-color;
    cursor: pointer;
  }
}
i {
  color: $secondary-color;
}
.price {
  position: relative;
  span{
    color: $secondary-color;
  }
}

// boxes img ---------------------------------------
.boxes {
  margin-top: 50px;
  margin-bottom: 80px;
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
      
    }
    .title {
      font-size: 39px;
    }
  }
}

.latest {
  background-image: url(../assets/img/cms-banner-03.jpg);
}
.popular {
  background-image: url(../assets/img/cms-banner-04.jpg);
}



</style>