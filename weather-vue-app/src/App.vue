<template>
  <div id="app">
    <Weather />
   
  </div>
</template>

<script>
import Weather from "./components/Weather.vue";

export default {
  name: "App",
  components: {
    Weather
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "montserrat", sans-serif;
}

#app {
  background-image: url("./assets/cold-pc.jpg");
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

/* @media screen and (min-width: 500px) {
 #app {
  background-image: url('./assets/cold-pc.jpg');
}
} */

main {
  min-height: 100vh;
  padding: 10%;

  background-image: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 0.25),
    rgba(0, 0, 0, 0.75)
  );
}
</style>
