  <script>
  import nav from '../data/nav-db.js';

  
  export default {
  name: 'myHeader',
  data(){
    return{
      nav
    }
  }
  }
  </script>


<template>
  
    <div class="header-top">
      <div class="container d-flex justify-between">
        <div class="boxes">
          <span>Wishlist(0)</span>
          <span>|</span>
          <span>Need Help?</span>
        </div>
        <div class="num">
          <span>Call 24/7 . 800-8754-987</span>
        </div>
      </div>
    </div>
    <div class="header-bottom">
      <div class="container d-flex justify-between align-center">
        <div class="logo">
          <img src="../assets/img/logo.png" alt="">
        </div>
        <nav>
          <ul class="d-flex">
            <li v-for="(link, index) in nav" :key="index"><a href="">{{ link.name }}</a></li>
          </ul>
        </nav>
        <div class="icons d-flex align-center">
          <span>
            <i class="fa-solid fa-magnifying-glass"></i>
          </span>
          <span>
            <i class="fa-regular fa-user"></i>
          </span>
          <span>
            <i class="fa-brands fa-shopify"></i>
            (0)
          </span>
        </div>
      </div>
    </div>
  
</template>


<style lang="scss" scoped>
.header-top {
  padding: 12px 0;
  border-bottom: 1px solid gray;
}
.header-bottom {
  padding: 10px;
}
li {
  margin: 20px 35px;
  a {
    text-transform: capitalize;
  }
}
.boxes {
  span {
    margin-right: 10px;
  }
}
.icons {
  i{
    font-size: 20px;
    margin-left: 35px;
  }
}

</style>