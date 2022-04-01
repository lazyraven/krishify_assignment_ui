<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <!-- <LeadGenerationForm /> -->
  <Comments></Comments>
</template>

<script>
// import LeadGenerationForm from "./components/LeadGenerationForm.vue";
import Comments from "./components/Comments.vue";

export default {
  name: "App",
  components: {
    Comments,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
