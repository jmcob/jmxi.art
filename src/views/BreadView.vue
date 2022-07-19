<template>
  <NavBar />
  <div class="hello">
    <h1>Gros pains de Vie</h1>
    <div class="cadre">
      <p>
        Vous trouverez ici de
        <a href="http://jmxi.art/pains/148-pains-de-vie.pdf"
          ><strong>gros pains de vie libres de droit</strong></a
        >, sélectionnés par notre équipe d'adorateurs du très saint sacrement.
        <br /><br />

        <strong>
          Ils sont plus gros, plus nourrissant, pour une meilleure prière avec
          notre Seigneur !</strong
        >
        <br /><br />Ils sont destinés à être utilisés dans l'Eglise.
        <br /><br />
        Il y a 83 pains issus de psaumes et 65 issus du reste de la Bible.
      </p>
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "GrosPains",
  components: {
    NavBar,
  },
};
</script>

<style>
strong {
  color: green;
  font-size: larger;
}
</style>
