<template>
  <div class="hello">
    <audio id="musicfx" loop="loop" autoplay="autoplay">
      <source src="../assets/summer.mp3" type="audio/mpeg">
    </audio>
    <img src="../assets/map.png" alt="">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <div class="myimg">

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js Ap'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
.myimg{
  width: 200px;
  height: 200px;
  background: url(../assets/map.png) no-repeat;
}
</style>
