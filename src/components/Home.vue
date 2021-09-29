<template>
  <div class = "Home">
  <img alt="aboutme img" src="../assets/aboutme.png">
  <h3>Who am I ?</h3>
  <p>I am a muslim junior software engineer who is curious and interested in computer science.</p> 
  <p>I have specific interest in areas like Backend developement, Data structure and algorithms and distributed systems.</p>
  <br>
  <h3>Selected projects</h3>
    <carousel :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="false">
    
    <slide>
      <h4>NLTK</h4>
      <img alt="aboutme img" src="../assets/nltk.gif">
      <p>NLTK is an open source natural language toolkit.</p>
      <p>I mainly contribute to tokenizer, tagger and sentiment analyzer modules.</p>
      <a href="https://github.com/nltk/nltk">Project Link</a>

    </slide>
    
    <slide>
    <h4>Orange Web-app</h4>
    <p>A Web-Application I did during my internship at Orange TeleCommunication Company</p>
    <p>The web-application is a portal for incoming applicants to apply for job postings on</p>
    <p>Technologies : Asp.net, C#, html, css, JS, Bootstrap, MySQL</p>
    </slide>

    <slide>
    <h4>FeTarek Mobile App</h4>
     <p>FeTare2k is Ride sharing mobile application similar to blabla car.</p>
     <p>Frontend is developed with flutter and dart</p>
     <p>REST API’s are designed in Spring, Java, and the database is developed with postgres</p>
      <a href="https://github.com/12mohaned/FeTare2k">Project Link</a>
    </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';
export default {
  name: 'Home',
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
