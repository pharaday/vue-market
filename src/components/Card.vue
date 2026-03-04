<script setup>
defineProps({
  title: String,
  imageUrl: String,
  price: Number
})
</script>

<template>
  <div class="relative bg-white border border-slate-100 rounded-3xl p-10 cursor-pointer transition hover:translate-y-[-10px] hover:shadow-xl">
    <img src="/like-2.svg" alt="like" class="absolute top-10 left-10">
    <img :src="imageUrl" alt="Sneaker" class="mb-4" />
    <p class="mb-4">{{ title }}</p>

    <div class="flex justify-between">
      <div class="flex flex-col">
        <span class="text-slate-400">Цена:</span>
        <b>{{ price }}$</b>
      </div>


      <img src="/plus.svg" alt="plus">
    </div>
  </div>
</template>

<style scoped></style>
