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
        <span>resident evil 3</span>
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
  height: 500px;
}
.jumbo-container {
  margin: 0 auto;
  padding: 150px 0;
  width: 60%;
  div {
    margin: 10px 0;
  }
}


</style>