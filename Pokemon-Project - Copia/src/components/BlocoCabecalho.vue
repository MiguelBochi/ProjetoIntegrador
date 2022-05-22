<script>
import { RouterLink } from "vue-router";

export default {
  components: { RouterLink },
};
</script>

<template>
  <header>
    <div class="menu"><RouterLink to="/Menu"></RouterLink></div>
    <div class="logo">Logo</div>
    <div class="genero">
      <RouterLink to="/" class="OpcoesCabecalho">Home</RouterLink>
      <RouterLink to="/Credits" class="OpcoesCabecalho">Credits</RouterLink>
    </div>
    <div class="pesquisa">
      <input class="BarraPesquisa" type="text" />
    </div>
  </header>
</template>
