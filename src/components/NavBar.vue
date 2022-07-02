<template>
  <nav>
    <router-link to="/">Home</router-link>
    ...

    <router-link to="/cross">Croix</router-link>
    ...
    <router-link to="/paint">Peintures</router-link>
    ...
    <router-link to="/testimony">Témoignage</router-link>
    ...
    <router-link to="/contact">Contact</router-link>
    ...
    <router-link to="/about">A propos</router-link>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>
