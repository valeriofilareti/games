<script>
import footer from '../data/footer-db.js';
export default {
name: 'myFooter',
data(){
  return {
    footer
  }
}
}
</script>
<template>
  <footer>
    <div class="container d-flex">
      <div v-for="(cols, index) in footer" :key="index" class="col">
        <h2>{{ cols.name}}</h2>
        <ul>
          <li v-for="(link, index) in cols.links" :key="index"><a href="#">{{ link }}</a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>


<style lang="scss" scoped>
footer {
  background-image: url(../assets/img/footer-bg.png);
}
.col {
  width: 30%;
  padding: 100px 20px;
  h2 {
    margin-bottom: 25px;
  }
  li {
    margin-bottom: 17px;
  }
}
a {
  color: grey;
}
</style>