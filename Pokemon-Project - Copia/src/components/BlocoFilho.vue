<script>
export default {
  data() {
    return {
      novos: [
        new URL("./img/1.jpg", import.meta.url).href,
        new URL("./img/2.jpg", import.meta.url).href,
        new URL("./img/3.jpg", import.meta.url).href,
        new URL("./img/86.jpg", import.meta.url).href,
        new URL("./img/anao.jpg", import.meta.url).href,
        new URL("./img/cavalo.jpg", import.meta.url).href,
        new URL("./img/cosplay.jpg", import.meta.url).href,
        new URL("./img/escola.jpg", import.meta.url).href,
        new URL("./img/espada.jpg", import.meta.url).href,
        new URL("./img/heroi.jpg", import.meta.url).href,
        new URL("./img/hunter.jpg", import.meta.url).href,
        new URL("./img/kuroko.jpg", import.meta.url).href,
      ],
      series: [
        new URL("./img/rango.jpg", import.meta.url).href,
        new URL("./img/romance.jpg", import.meta.url).href,
        new URL("./img/SAO.jpg", import.meta.url).href,
        new URL("./img/titan.jpg", import.meta.url).href,
        new URL("./img/volei.jpg", import.meta.url).href,
        new URL("./img/hunter.jpg", import.meta.url).href,
        new URL("./img/onepiece.jpg", import.meta.url).href,
        new URL("./img/momongas.jpg", import.meta.url).href,
        new URL("./img/espada.jpg", import.meta.url).href,
        new URL("./img/heroi.jpg", import.meta.url).href,
        new URL("./img/cosplay.jpg", import.meta.url).href,
        new URL("./img/kuroko.jpg", import.meta.url).href,
      ],
      acao: [
        new URL("./img/1.jpg", import.meta.url).href,
        new URL("./img/2.jpg", import.meta.url).href,
        new URL("./img/3.jpg", import.meta.url).href,
        new URL("./img/86.jpg", import.meta.url).href,
        new URL("./img/anao.jpg", import.meta.url).href,
        new URL("./img/cavalo.jpg", import.meta.url).href,
        new URL("./img/titan2.jpg", import.meta.url).href,
        new URL("./img/escola.jpg", import.meta.url).href,
        new URL("./img/espada.jpg", import.meta.url).href,
        new URL("./img/heroi.jpg", import.meta.url).href,
        new URL("./img/hunter.jpg", import.meta.url).href,
        new URL("./img/kuroko.jpg", import.meta.url).href,
      ],
    };
  },
};
</script>
<template>
  <div><p class="titulo">Novos</p></div>
  <div class="Pai">
    <div v-for="(imagem, i) in novos" :key="i">
      <img class="Filho" :src="imagem" alt="" />
    </div>
  </div>
  <div><p class="titulo">Series</p></div>
  <div class="Pai">
    <div v-for="(imagem, i) in series" :key="i">
      <img class="Filho" :src="imagem" alt="" />
    </div>
  </div>
  <div><p class="titulo">Ação</p></div>
  <div class="Pai">
    <div v-for="(imagem, i) in acao" :key="i">
      <img class="Filho" :src="imagem" alt="" />
    </div>
  </div>
</template>
