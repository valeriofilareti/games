<script>
export default {
name: 'Sponsors'
}
</script>

<template>
  <div class="container">
    <div class="sponsors d-flex justify-between">
      <img src="../assets/img/brand-01.png" alt="">
      <img src="../assets/img/brand-02.png" alt="">
      <img src="../assets/img/brand-03.png" alt="">
      <img src="../assets/img/brand-04.png" alt="">
      <img src="../assets/img/brand-05.png" alt="">
    </div>
  </div>
</template>


<style lang="scss" scoped>
.sponsors {
  width: 100%;
  height: 200px;
  overflow: scroll;
  border-top: 2px solid gray;
}
img {
  width: 50%;
  height: 50%;
  margin: 30px;

}

</style>