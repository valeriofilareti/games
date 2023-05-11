  <script>
  export default {
  name: 'SpecialCategories'
  }
  </script>

<template>
  <div class="container">
    <h1 class="section-title">special category</h1>
    <div class="boxes d-flex justify-between">
      <div class="box"></div>
      <div class="box"></div>
      <div class="box"></div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container {
  text-align: center;
  padding-top: 90px;
}
.box {
  width: 32%;
  aspect-ratio: 4/5;
  border: 1px solid white;
}
</style>