<template>
  <NavBar />
  <div class="about">
    <h1>Coded by Jean-Maxime Cobac</h1>
    <p>in May 2022.</p>
    <p>
      <a href="mailto:ola@jmax.dev">contactez-moi !</a>
      <br />
      <a href="http://www.jmax.dev"
        >Vous recherchez peut-être un développeur web ?</a
      >
    </p>
    <img alt="about us ipad image" src="../assets/about.png" />

    <p>C'est déja la troisième version de jmxi.art.</p>
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
