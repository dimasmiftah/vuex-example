<template>
  <div id="app">
    <product-list-one v-bind:products="products"></product-list-one>
    <product-list-two v-bind:products="products"></product-list-two>
  </div>
</template>

<script>
import productListOne from './components/product-list-one.vue'
import productListTwo from './components/product-list-two.vue'
export default {
  components: {
    'product-list-one' : productListOne,
    'product-list-two' : productListTwo,
  },
  data () {
    return {
      
    }
  }
}
</script>

<style>
</style>
