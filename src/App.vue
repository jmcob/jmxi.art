<template>
  <router-view />
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
  color: rgb(17, 17, 181);
}
h2 {
  color: rgb(17, 17, 181);
}
.hello {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.cadre {
  /* background: rgb(10, 145, 255);
  background: linear-gradient(
    318deg,
    rgba(10, 145, 255, 1) 0%,
    rgba(90, 181, 255, 1) 3%,
    rgba(152, 209, 255, 1) 7%,
    rgba(218, 238, 255, 1) 89%,
    rgba(255, 255, 255, 1) 100%
  ); */
  border-radius: 15px;
  max-width: 550px;
  padding: 0 45px 15px 45px;
  /* box-shadow: 1px 1px midnightblue; */
  border: 1px solid crimson;
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
