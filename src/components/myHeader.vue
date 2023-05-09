  <script>
  export default {
  name: 'myHeader'
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
      <div class="container d-flex justify-between">
        <div class="logo"><h1>LOGO</h1></div>
        <nav>
          <ul class="d-flex">
            <li><a href="">link</a></li>
            <li><a href="">link</a></li>
            <li><a href="">link</a></li>
            <li><a href="">link</a></li>
            <li><a href="">link</a></li>
            <li><a href="">link</a></li>
          </ul>
        </nav>
        <div class="icons">
        <span>X</span><span>X</span><span>X</span>
        </div>
      </div>
    </div>
  
</template>


<style lang="scss" scoped>
.header-top {
  padding: 12px 0;
  border-bottom: 1px solid gray;
}
.boxes {
  span {
    margin-right: 10px;
  }
}

</style>