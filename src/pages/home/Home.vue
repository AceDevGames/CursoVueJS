<template>
<span>
<publicar-conteudo-vue />
  <card-conteudo-vue perfil="https://materializecss.com/images/yuna.jpg"
    nome="Maria da Couve"
    data="26/07/18 12:30"
  >
    <card-detalhe-vue img="https://materializecss.com/images/sample-1.jpg"
      titulo=""
      txt="I am a very simple card. I am good at containing small bits of information.
        I am convenient because I require little markup to use effectively."/>
  </card-conteudo-vue>
</span>

</template>

<script>
import CardConteudoVue from '@/Components/social/CardConteudoVue'
import PublicarConteudoVue from '@/Components/social/PublicarConteudoVue'
import CardDetalheVue from '@/Components/social/CardDetalheVue'

export default {
  name: 'Home',
  data () {
    return {
    }
  },
  components: {
    CardConteudoVue,
    CardDetalheVue,
    PublicarConteudoVue
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
