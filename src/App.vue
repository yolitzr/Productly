<template>
  <Home />
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');

*, 
*:after, *:before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
}
</style>
