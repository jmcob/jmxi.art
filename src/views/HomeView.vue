<template>
  <NavBar />
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to jmxi.art" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import NavBar from "@/components/NavBar.vue";
export default {
  name: "HomeView",
  components: {
    HelloWorld,
    NavBar,
  },
};
</script>

<style scoped>
img {
  width: 275px;
  max-width: 65vw;
}
</style>
