<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
import BlocoCabecalho from "./components/BlocoCabecalho.vue";
import BlocoRodape from "./components/BlocoRodape.vue";
export default {
  components: { MenuLateral, BlocoCabecalho, BlocoPrincipal, BlocoRodape },
};
</script>
<template>
  <MenuLateral />
  <BlocoCabecalho />
  <BlocoPrincipal />
  <BlocoRodape />
</template>
<style></style>
