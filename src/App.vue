<template>
  <div id="app">
      <product-hero></product-hero>
      <product-info></product-info>
      <page-footer></page-footer>
  </div>
</template>

<script>
import ProductHero from '@/components/ProductHero.vue'
import ProductInfo from '@/components/ProductInfo.vue'
import PageFooter from '@/components/PageFooter.vue'

export default {
  name: 'App',
  components: {
    ProductHero,
    ProductInfo,
    PageFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
