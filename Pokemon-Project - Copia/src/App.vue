<script>
import BlocoCabecalho from "./components/BlocoCabecalho.vue";
import BlocoRodape from "./components/BlocoRodape.vue";
import { RouterView } from "vue-router";

export default {
  components: { BlocoCabecalho, RouterView, BlocoRodape },
};
</script>

<template>
  <BlocoCabecalho />
  <main><RouterView /></main>
  <BlocoRodape />
</template>
