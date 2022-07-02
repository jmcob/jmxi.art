<template>
  <NavBar />
  <h1><em>Erreur</em> <strong>quatre cent quatre</strong></h1>
  <p>404 error</p>
  <p>
    La page que vous demandez n'a pas été trouvée.
    <br />
    <strong class="back-home">
      Je vous suggère de vous rendre
      <router-link to="/">à l'accueil de jmxi.art</router-link></strong
    ><br />
    ou, au choix, de recomposer un logo pour
    <a href="google.com">Google.</a>
  </p>
  <img src="../assets/404.jpg" alt="404 palette de couleurs" />
  <NavBar />
</template>
<style scoped>
img {
  width: 50%;
  max-width: 450px;
}
.back-home {
  font-size: larger;
}
</style>
<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "NotFoundView",
  components: {
    NavBar,
  },
  created() {
    document.title = "404 - Développeur Web Fullstack - Jean-Maxime Cobac";
  },
};
</script>
