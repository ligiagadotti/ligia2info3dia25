<script>
import ComponenteNaoSei from "@/components/ComponenteNaoSei.vue";
export default {
  components: { ComponenteNaoSei },
};
</script>
<template>
  <main id="content">
    <ComponenteNaoSei titulo="Bloco 1" :nomes="['Heloisa', 'Eduardo']" />
    <ComponenteNaoSei
      titulo= "URGENTE"
      class="alerta"
      :nomes="['Eduardo', 'Wedley']"
    />
    <ComponenteNaoSei />
    <ComponenteNaoSei class="alerta" />
    <ComponenteNaoSei />
    <ComponenteNaoSei />
  </main>
</template>
<style>
</style>
