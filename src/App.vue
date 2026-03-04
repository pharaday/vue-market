<script setup>
import Header from '@/components/Header.vue'
import CardList from '@/components/CardList.vue'
</script>

<template>
  <div class="w-4/5 mt-15 m-auto bg-white rounded-2xl shadow-2xl">
    <Header />

    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>

      <CardList />
    </div>
  </div>

  <Test />
</template>

<style scoped></style>
