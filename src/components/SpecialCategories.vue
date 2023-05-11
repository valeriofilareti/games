  <script>
  export default {
  name: 'SpecialCategories'
  }
  </script>

<template>
  <div class="container">
    <h1 class="section-title">Special Category</h1>
    <div class="boxes d-flex justify-between">
      <div class="box">
        <img src="../assets/img/category-image-01-446x550_t.jpg" alt="">
        <div class="text d-flex">
          <span class="name">Batman</span>
          <a href="">Shop Now</a>
        </div>
      </div>
      <div class="box">
        <img src="../assets/img/category-image-02-446x550_t.jpg" alt="">
        <div class="text d-flex">
          <span class="name">Bayonetta</span>
          <a href="">Shop Now</a>
        </div>
      </div>
      <div class="box">
        <img src="../assets/img/category-image-03-446x550_t.jpg" alt="">
        <div class="text d-flex">
          <span class="name">Dark Souls</span>
          <a href="">Shop Now</a>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
@import '../scss/general/vars';
.container {
  text-align: center;
  padding-top: 90px;
}
.box {
  width: 32%;
  aspect-ratio: 4/5;
  border: 1px solid white;
  position: relative;
  img {
    width: 100%;
  }
  .text {
    width: 100%;
    height: 100px;
    background-color: rgba(30, 20, 39, 0.5);
    position: absolute;
    bottom: 0;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 10px;
    span {
      padding: 7px 0;
      font-size: 22px;
    }
    a {
      color: $secondary-color;
    }

  }
}
</style>