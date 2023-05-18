<template>
  <div id="app">
    <Navbar></Navbar>
    <Product></Product>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './components/MyNavbar.vue';
import Product from './components/MyProduct.vue';
import Footer from './components/MyFooter.vue';
export default {
  name: 'App',
  components: {
    Navbar,
    Product,
    Footer
  }
}
</script>

<style>

</style>
