<template>
  <nav>
    <router-link to="/">Page d'accueil</router-link> |

    <router-link to="/cross">Croix</router-link> |
    <router-link to="/paint">Peintures</router-link> |
    <router-link to="/testimony">Testimony</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>
