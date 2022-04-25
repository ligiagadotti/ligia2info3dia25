<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoCabecalho from "@/components/BlocoCabecalho.vue";
import BlocoRodape from "@/components/BlocoRodape.vue";
import BlocoPrincipal from "@/components/BlocoPrincipal.vue";

export default {
  components: { BlocoPrincipal, BlocoCabecalho, BlocoRodape, MenuLateral },
};
</script>
<template>
  <MenuLateral />
  <BlocoPrincipal />
  <BlocoCabecalho />
  <BlocoRodape />
</template>
<style></style>
