<script>
import NovoBloco from "@/NovoBloco.vue";
export default {
  components: { NovoBloco },
  data() {
    return {
      alunos1: ["Heloisa", "Eduardo"],
    };
  },
};
</script>
<template>
  <main id="content">
    <NovoBloco titulo="Bloco 1" :nomes="['Heloisa', 'Eduardo']" />
    <NovoBloco titulo="URGENTE" class="alert" :nomes="['Eduardo', 'Wedley']" />
    <NovoBloco class="alert" />
    <NovoBloco />
    <NovoBloco />
    <NovoBloco :nomes="alunos1" />
  </main>
</template>
<style></style>
