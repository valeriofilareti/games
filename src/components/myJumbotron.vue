  <script>
  export default {
  name: 'myJumbotron'
  }
  </script>
<template>
  <div class="jumbotron">
    <div class="jumbo-container">
      <div class="stock">
        <span class="yellow-box">
          upcoming stock
        </span>
      </div>
      <div class="title">
        <span>resident evil 3 remake</span>
      </div>
      <div class="cta">
        <span>shop now</span>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.jumbotron {
  background-image: url(../assets/img/jumbo1.jpeg);
  background-size: cover;
  height: 550px;
}
.jumbo-container {
  width: 701px;
  padding: 170px 195px;
  div {
    margin: 10px 0;
  }
}
.stock {
  .yellow-box {
    display: inline-block;
    padding: 5px 15px;
    font-size: 18px;
  }
}
.title {
  span {
    font-size: 50px;
    padding: 0;
    line-height: 50px;
    margin-top: 20px;
  }
}
.cta {
  padding-top: 60px;
  span {
    font-size: 12px;
    border: 1px solid white;
    padding: 5px 8px;
    background-color: white;
    color: black;
    cursor: pointer;
    margin-top: 20px;
  }
}


</style>