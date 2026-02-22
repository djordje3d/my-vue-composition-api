<script setup>
import { ref } from 'vue'
import ProductDisplay from '@/components/ProductDisplay.vue'

const cart = ref(0)
const premiumTestAppVue = true

</script>
  
<template>
  <div class="nav-bar"></div>
  <div class="cart">Cart({{ cart }})</div>
  <ProductDisplay :premium="premiumTestAppVue"></ProductDisplay>
</template>