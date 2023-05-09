  <script>
  import myHeader from './components/myHeader.vue';
  import myJumbotron from './components/myJumbotron.vue';
  import myMain from './components/myMain.vue';
  import myFooter from './components/myFooter.vue';
  export default {
  name: 'App',
  data(){
    return{

    }
  },
  components: {
    myHeader,
    myJumbotron,
    myMain,
    myFooter
  }
  }
  </script>

<template>
  <body>
    <myHeader/>
    <myJumbotron/>
    <myMain/>
    <myFooter/>
  </body>
</template>


<style lang="scss">
@import './scss/main.scss';
body {
  background-image: url(./assets/img/body-bg.jpg);
}


</style>