<template>
  <nav>
    <router-link to="/">Page d'accueil</router-link> |

    <router-link to="/cross">Croix</router-link> |
    <router-link to="/paint">Peintures</router-link> |
    <router-link to="/testimony">Testimony</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
  <nav>
    <router-link to="/">Page d'accueil</router-link> |

    <router-link to="/cross">Croix</router-link> |
    <router-link to="/paint">Peintures</router-link> |
    <router-link to="/testimony">Testimony</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
nav {
  font-size: x-large;
}
img {
  border-radius: 10px;
}
nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: midnightblue;
}
h2 {
  color: midnightblue;
}
</style>
