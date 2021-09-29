<template>
  <div class = "Moments">
  <h3>Moments</h3>
    <carousel :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="false">
    
    <slide>
      <h4>During my internship at orange</h4>
      <img alt="aboutme img" src="../assets/orange.png">
      <p>Last day of my internship at Orange(I am the one in the middle wearing white)</p>
    </slide>
    
    <slide>
    <h4>Exploring Frankfurt woods</h4>
      <img alt="aboutme img" src="../assets/explore.png">

    <p>A photobomb while exploring in the woods of North Frankfurt</p>
    </slide>

    <slide>
    <h4>During my internship at Dell</h4>
     <img alt="aboutme img" src="../assets/dell_internship.jpeg">
     <p>Me wearing Dell Technologies T-shirt during summer internship</p>
    </slide>

    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';
export default {
  name: 'Moments',
  components: {
    Carousel,
    Slide
  }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

</style>
