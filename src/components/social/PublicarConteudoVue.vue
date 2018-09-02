<template>
  <div class="row">
    <GridVue class="input-field" tamanho="12">
      <textarea v-model="conteudo" id="conteudoID" class="materialize-textarea"></textarea>
      <label for="conteudoID">O que está acontecendo?</label>
    </GridVue>
    <p>
      <grid-vue v-if="conteudo" class="btn waves-effect waves-light" tamanho="2 offset-s10">Publicar</grid-vue>
    </p>
  </div>
</template>

<script>
import GridVue from '@/Components/layouts/GridVue'
export default {
  name: 'PublicarConteudoVue',
  props: [
  ],
  data () {
    return {
      conteudo: ''
    }
  },
  components: {
    GridVue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
