<template>
  <NavBar />
  <hr />
  <br />

  <h1>Peintures</h1>
  <div class="card">
    <h2>La fleur - 2009</h2>
    <figure>
      <img src="../assets/paintings/WP_20150809_001_001.jpg" alt="la fleur" />
    </figure>
  </div>
  <hr />
  <div class="card">
    <h2>Animal collective - 2009</h2>
    <figure>
      <img
        src="../assets/paintings/WP_20150809_002_001.jpg"
        alt="Animal collective"
      />
    </figure>
  </div>
  <hr />
  <div class="card">
    <h2>Langues de feu : la Pentecôte - 2019</h2>
    <figure>
      <img
        src="../assets/paintings/IMG_0016.jpeg"
        alt="Langues de feu : la Pentecôte"
      />
    </figure>
  </div>
  <hr />
  <div class="card">
    <h2>Chocobo - 2019</h2>
    <figure>
      <img src="../assets/paintings/IMG_0036.jpeg" alt="Chocobo" />
    </figure>
  </div>
  <hr />
  <div class="card">
    <h2>Pour Maman - 2019</h2>
    <figure>
      <img src="../assets/paintings/IMG_0059.jpeg" alt="Pour Maman" />
    </figure>
  </div>
  <hr />
  <div class="card">
    <h2>La Reine des Cieux - 2019</h2>
    <figure>
      <img src="../assets/paintings/IMG_0061.jpeg" alt="La Reine des Cieux" />
    </figure>
  </div>
  <br />
  <hr />
  <NavBar />
</template>
<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "PaintingView",
  components: {
    NavBar,
  },
};
</script>
<style scoped>
.card img {
  width: 80vw;
  max-width: 600px;
}
</style>
