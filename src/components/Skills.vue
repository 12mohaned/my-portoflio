<template>
  <div class = "Skills">
  <img alt="aboutme img" src="../assets/skills.png">
  <h3>Skills</h3>
  <table>
  <tr>
    <td><img alt="aboutme img" src="../assets/Django.png"></td>
    <td><img alt="aboutme img" src="../assets/flask.png"></td>
    <td><img alt="aboutme img" src="../assets/python.png"></td>
    <td><img alt="aboutme img" src="../assets/Mysql.png"></td>
    <td><img alt="aboutme img" src="../assets/Postgresql.png"></td>
  </tr>
  <tr>
    <td><img alt="aboutme img" src="../assets/java.png"></td>
    <td><img alt="aboutme img" src="../assets/selenium.png"></td>
    <td><img alt="aboutme img" src="../assets/golang_icon.png"></td>
    <td><img alt="aboutme img" src="../assets/github.png"></td>
    <td><img alt="aboutme img" src="../assets/html.png"></td>
  </tr>
  </table>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  }
</script>
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