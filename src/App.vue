<template>
  <span>
    <header>
  <nav-bar logo="Social" url="#" cor ="light-blue accent-3"/>
    </header>

  <main>
    <div class="container">
      <div class="row">
        <grid-vue tamanho="4">
          <card-menu-vue>
            <div class="row valign-wrapper">
              <grid-vue tamanho="4">
                <img src="https://materializecss.com/images/yuna.jpg" alt="" class="circle responsive-img"> <!-- notice the "circle" class -->
              </grid-vue>
              <grid-vue tamanho="8">
                <span class="black-text">
                  <h6>Maria da Couve</h6>
                  Add the "circle" class to it to make it appear circular.
                </span>
              </grid-vue>
            </div>
          </card-menu-vue>
          <card-menu-vue>
            <h3>Teste</h3>
          </card-menu-vue>
        </grid-vue>
        <grid-vue tamanho="8">
          <router-view/>
        </grid-vue>
      </div>
    </div>
  </main>

<footer-vue cor="light-blue accent-3" logo="Social" descricao="Teste de descrição!" ano="2018">

  <li><a class="grey-text text-lighten-3" href="#!">Home</a></li>
  <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
  <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
  <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>

</footer-vue>
  </span>
</template>

<script>
import NavBar from '@/Components/layouts/Navbar'
import FooterVue from '@/Components/layouts/FooterVue'
import GridVue from '@/Components/layouts/GridVue'
import CardMenuVue from '@/Components/layouts/CardMenuVue'
export default {
  name: 'App',
  components: {
    NavBar,
    FooterVue,
    GridVue,
    CardMenuVue
  }
}
</script>

<style>
</style>
