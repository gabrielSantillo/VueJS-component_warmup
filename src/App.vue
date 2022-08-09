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
* {
    margin: 0;
    padding: 0;
    font-family: "Garamond", "Lucida Sans", "Lucida Sans Regular", "Lucida Grande", "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  }
  
  body {
    min-height: 100vh;
    place-items: center;
    width: 100%;
  }
  
  img, svg, iframe {
    width: 100%;
}

</style>
