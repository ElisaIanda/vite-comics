
<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import Banner from "./components/Banner.vue"
import ThePiePagina from "./components/ThePiePagina.vue";

export default {
  components: {
  TheHeader,
  TheFooter,
  Banner,
  ThePiePagina,
}
}
</script>

<template>
  <TheHeader></TheHeader>
<main class="p-3">
  <div class="container">
    <h4> Contect Goes Here</h4>
  </div>
</main>
  <Banner></Banner>

  <TheFooter></TheFooter>

  <ThePiePagina></ThePiePagina>
</template>

<style lang="scss">
@use"../src/styles/partials/variable" as *;
main{
  background-color: black;
}

h4{
  color: $my-color-text;
}
</style>

