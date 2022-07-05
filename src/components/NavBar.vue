<template>
  <nav>
    <div class="router title">
      <router-link to="/">jmxi.art</router-link>
    </div>
    <div class="router">
      <router-link to="/cross">Croix</router-link>
    </div>
    <div class="router">
      <router-link to="/paint">Peintures</router-link>
    </div>
    <div class="router">
      <router-link to="/testimony">Témoignage</router-link>
    </div>
    <div class="router">
      <router-link to="/contact">Contact</router-link>
    </div>
    <div class="router">
      <router-link to="/grospains">Pains de Vie</router-link>
    </div>
    <div class="router"><a href="https://www.jmax.dev/">Code</a></div>
    <div class="router">
      <router-link to="/about">A propos</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
nav {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
nav a {
  text-decoration: none;
}
nav a:hover {
  color: rgb(35, 83, 255);
}
.router {
  margin: 12px;
}
</style>
