<template>
  <NavBar />
  <div class="hello">
    <h1>Gros pains de Vie</h1>
    <div class="cadre">
      <p>
        Vous trouverez ici de
        <strong>gros pains de vie libres de droit</strong>, sélectionnés par
        notre équipe d'adorateurs du très saint sacrement. <br /><br />

        <strong>
          Ils sont plus gros, plus nourrissant, pour une meilleure prière avec
          notre Seigneur !</strong
        >
        <br /><br />Ils sont destinés à être utilisés dans l'Eglise.
        <br /><br />
        Il y a 83 pains issus de psaumes et 65 issus du reste de la Bible.
      </p>
      <h2>
        <a href="@/assets/pains/148-pains-de-vie.pdf"
          >Télécharger 148 gros pains de Vie (PDF)</a
        >
      </h2>
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
