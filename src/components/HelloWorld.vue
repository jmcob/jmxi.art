<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <q
      >Qu'êtes-vous allés voir au désert ? <br />
      Un roseau agité par le vent ? <br />
      Mais qu'êtes-vous allés voir ? <br />
      Un homme habillé de tenues élégantes ?</q
    >
    <p class="quote">Evangile de Jésus Christ selon Matthieu 11,8</p>

    <p class="p">
      Ce petit site sert à extérioriser certaines de mes créations.
      <br />
      <br />
      <em
        >Si quelque chose vous plait,
        <router-link to="/contact">contactez-moi !</router-link></em
      >
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

q {
  font-style: italic;
}
.quote {
  text-align: center;
}
.p {
  font-size: large;
}
</style>
