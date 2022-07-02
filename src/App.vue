<template>
  <router-view />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dosis:wght@200;500;700&family=Pacifico&display=swap");

.material-symbols-outlined {
  font-variation-settings: "FILL" 0, "wght" 400, "GRAD" 200, "opsz" 48;
}

* {
  background: #082139;
}

#app {
  font-family: "Dosis", sans-serif;

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}

img {
  border-radius: 10px;
}
nav {
  padding: 30px;
  font-size: xx-large;
  font-family: "Pacifico", cursive;
}

nav a {
  font-weight: bold;
  color: white;
}

nav a.router-link-exact-active {
  color: rgb(35, 83, 255);
}
p,
q {
  font-size: large;
}
h2 {
  color: rgb(35, 83, 255);
}
.hello {
  display: flex;
  flex-direction: column;
  align-items: center;
}
a {
  color: rgb(105, 132, 255);
}
a:visited {
  color: rgb(190, 202, 255);
}
.cadre {
  border-radius: 15px;
  max-width: 550px;
  padding: 0 45px 15px 45px;
  border: 1px solid rgb(0, 193, 0);
  margin-top: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-bottom: 0px;
}

.cadre img {
  padding: 0px;
  margin: 0px;
}
.content {
  position: relative;
  bottom: 45px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.img {
  box-sizing: border-box;
  box-shadow: 5px 5px 5px white;
  width: 81px;
  height: 81px;
}
</style>
