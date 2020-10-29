<template>
  <galaga />
</template>

<script>
import Galaga from "./components/Galaga";

export default {
  name: "App",
  components: {
    Galaga
  }
};
</script>

<style>
html {
  overflow: hidden;
  background-color: black;
}
#app {
  margin: 0;
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;

  height: 100vh;
}
</style>
