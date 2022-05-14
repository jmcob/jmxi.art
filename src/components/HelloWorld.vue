<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Vraiment soyez les bienvenus ... !</h2>
    <p>
      Ce petit site sert à extérioriser un peu mes créations. Si quelque chose
      vous plait,
      <a href="mailto:ola@jmax.dev">n'hésitez pas à me contacter !</a>
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
