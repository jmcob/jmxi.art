<template>
  <NavBar />
  <hr />
  <br />
  <div class="about">
    <h1>Coded by Jean-Maxime Cobac</h1>
    <p>
      Si vous le souhaitez,
      <router-link to="/contact">contactez-moi.</router-link> <br /><br />
      <a href="http://www.jmax.dev"
        >Peut-être recherchez-vous un développeur web ?</a
      >
    </p>
    <img alt="about us ipad image" src="../assets/about.png" />

    <p>C'est déja la troisième version de jmxi.art, lancée en mai 2022.</p>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "AboutView",
  components: {
    NavBar,
  },
};
</script>

<style scoped>
img {
  width: 80vw;
  max-width: 400px;
}
p {
  font-size: large;
}
</style>
