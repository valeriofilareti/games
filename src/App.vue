  <script>
  import Swiper from 'https://cdn.jsdelivr.net/npm/swiper@9/swiper-bundle.esm.browser.min.js'
  import myHeader from './components/myHeader.vue';
  import myJumbotron from './components/myJumbotron.vue';
  import myMain from './components/myMain.vue';
  import myReviews from './components/myReviews.vue';
  import myFooter from './components/myFooter.vue';
  export default {
  name: 'App',
  data(){
    return{
      Swiper
    }
  },
  components: {
    myHeader,
    myJumbotron,
    myMain,
    myReviews,
    myFooter
  }
  }
  </script>

<template>
  <body>
    <myHeader/>
    <myJumbotron/>
    <myMain/>
    <myReviews />
    <myFooter/>
  </body>
</template>


<style lang="scss">
@import './scss/main.scss';
body {
  background-image: url(./assets/img/body-bg.jpg);
}
</style>