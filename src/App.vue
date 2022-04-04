<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Comments></Comments>
  <GenerationForm></GenerationForm>
  <FarmerDetails></FarmerDetails>
</template>

<script>
import Comments from "./components/Comments.vue";
import GenerationForm from "./components/GenerationForm.vue";
import FarmerDetails from "./components/FarmerDetails.vue";

export default {
  name: "App",
  components: {
    Comments,
    GenerationForm,
    FarmerDetails,
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
