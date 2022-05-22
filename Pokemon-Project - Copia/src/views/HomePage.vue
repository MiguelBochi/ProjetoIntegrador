<script>
import BlocoFilho from "../components/BlocoFilho.vue";

export default {
  components: { BlocoFilho},
};
</script>

<template>
  <div id="content">
    <div id="carrossel">
      <img class="cavalinho" src="../components/img/mago3.jpg" alt="" />
      <img class="cavalinho" src="../components/img/mago.jpg" alt="" />
      <img class="cavalinho" src="../components/img/magos.jpg" alt="" />
      <img class="cavalinho" src="../components/img/momongas.jpg" alt="" />
      <img class="cavalinho" src="../components/img/onepiece.jpg" alt="" />
    </div>
    <BlocoFilho />
  </div>
</template>

<style>
.cavalinho:hover {
  width: 249px;
}
</style>
