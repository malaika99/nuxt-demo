<template>
  <div class="grid grid-cols-4 gap-5">
    <div v-for="p in products">
      <ProductCard :product="p"/>
    </div>
  </div>
</template>

<script setup>
import ProductCard from '../../components/ProductCard.vue';

  definePageMeta({
    layout: 'products'
  })

  // fetch the products
  const { data: products } = await useFetch('https://fakestoreapi.com/products')

  useHead({
    title: 'Nuxt Merch',
    meta: [
      { name:'description', content: 'Maalika' }
    ]
  })
</script>

<style scoped>

</style>
