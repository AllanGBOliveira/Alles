<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" class="block mx-auto "> -->
  <Landing ></Landing>
</template>

<script>
import Landing from "./components/Landing.vue";

export default {
  name: "App",
  components: {
    Landing,
  },
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body{
  margin: 0;
  padding: 0;
}
</style>
