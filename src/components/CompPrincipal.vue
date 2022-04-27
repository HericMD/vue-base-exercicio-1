<script>
import NovoBloco from "@/components/NovoBloco.vue";
export default {
  components: { NovoBloco },
};
</script>
<template>
  <main id="content">
    <NovoBloco titulo="Bloco 1" :nomes="['Heloisa', 'Eduardo']" />
    <NovoBloco titulo="URGENTE" class="alert" :nomes="['Eduardo', 'Wedley']" />
    <NovoBloco class="alert" />
    <NovoBloco />
    <NovoBloco />
    <NovoBloco />
  </main>
</template>
<style></style>
