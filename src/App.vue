
<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import Banner from "./components/Banner.vue"
import ThePiePagina from "./components/ThePiePagina.vue";
import AllCard from "./components/AllCard.vue"
import Jumbotron from "./components/Jumbotron.vue";

export default {
  components: {
    TheHeader,
    TheFooter,
    Banner,
    ThePiePagina,
    AllCard,
    Jumbotron,
  }
}
</script>

<template>
  <TheHeader></TheHeader>
  <Jumbotron></Jumbotron>
  <main class="p-3">
    <AllCard></AllCard>
    <div class="d-flex justify-content-center mb-3">
      <button>
        LOAD MORE
      </button>
    </div>
  </main>
  <Banner></Banner>

  <TheFooter></TheFooter>

  <ThePiePagina></ThePiePagina>
</template>

<style lang="scss">
@use"../src/styles/partials/variable" as *;

main {
  background-color: #1c1c1c;
}

button{
  color: $my-color-text;
    background-color: $my-color-primary;
    border: none;
    padding: 0.5rem;
    font-weight: 700;
}

</style>

