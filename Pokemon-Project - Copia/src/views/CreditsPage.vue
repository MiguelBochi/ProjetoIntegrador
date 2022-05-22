<script>
export default {
  data() {
    return {
      Alex: [new URL("../components/img/Alex.png", import.meta.url).href],
      Miguel: [new URL("../components/img/Miguel.jpg", import.meta.url).href],
    };
  },
};
</script>

<template>
  <div class="Credits">
    <div>
      <article class="A1">
        <ul>
          <li>Alex Monteiro de Magalhães</li>
          <li>Idade: 18 anos</li>
          <li>Nascido em Joinville, SC</li>
          <li>Cursando 2 ano do ensino médio</li>
        </ul>
      </article>
      <aside class="As1">
        <div v-for="(imagem, i) in Miguel" :key="i">
          <img class="Foto" :src="imagem" alt="" />
        </div>
      </aside>
    </div>
    <div>
      <aside class="As2">
        <div v-for="(imagem, i) in Alex" :key="i">
          <img class="Foto" :src="imagem" alt="" />
        </div>
      </aside>
      <article class="A2">
        <ul>
          <li>Miguel Bochi Barros</li>
          <li>Idade: 15 anos</li>
          <li>Nascido em Cascavel, PR</li>
          <li>Cursando 2 ano do ensino médio</li>
        </ul>
      </article>
    </div>
  </div>
</template>
