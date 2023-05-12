  <script>
  export default {
  name: 'Reviews'
  }
  </script>

<template>
  <div class="reviews d-flex">
    <div class="img">
      <img src="../assets/img/t5-1-100x100_left.jpg" alt="">
    </div>
    <div class="employ">
      <span class="name">luies charls</span>
      <span class="occupation">(Web designer)</span>
    </div>
    <div class="declaration">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nam mollitia minima illum sapiente, eligendi maxime esse voluptatum inventore quisquam perspiciatis assumenda, dolorem eos dolores tenetur animi nisi aliquam quam dolore nulla quibusdam facere corrupti magnam debitis. Quidem inventore molestiae, aut commodi eos doloremque delectus adipisci aliquid rerum nulla quas cumque.</div>
  </div>
</template>


<style lang="scss" scoped>
@import '../scss/general/vars';
.reviews {
  width: 100%;
  height: 500px;
  background-image: url(../assets/img/parallax.jpg);
  background-position: center;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 90px;
  div {
    margin: 20px 8px;
  }
  .employ {
    text-transform: capitalize;
    font-weight: 600;
    span {
      padding: 7px;
    }
    .occupation {
      color: $secondary-color;
    }
  }
  .declaration {
    text-align: center;
    color: gray;
    line-height: 38px;
  }
}
img {
  border-radius: 50%;
  border: 3px solid $secondary-color;
}
</style>