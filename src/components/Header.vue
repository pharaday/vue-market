<script setup lang="ts">
</script>

<template>
  <header class="flex justify-between px-12 py-8 border-b border-gray-200">
    <div class="flex items-center w-100 gap-4">
      <img src="/public/logo.png" alt="" class="w-10">
      <div class="flex flex-col">
        <h2 class="text-xl font-bold uppercase">REACT SNEAKERS</h2>
        <p class=""> Магазин лучших кроссовок</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center gap-2 text-gray-500 hover:text-black cursor-pointer">
        <img src="/public/cart.svg" alt="">
        <span>1205 руб.</span>
      </li>
      <li class="flex items-center gap-2 text-gray-500 hover:text-black cursor-pointer">
        <img src="/public/heart.svg" alt="">
        <span>Закладки</span>
      </li>
      <li class="flex items-center gap-2 text-gray-500 hover:text-black cursor-pointer">
        <img src="/public/profile.svg" alt="">
        <span>Профиль</span>
      </li>
    </ul>
  </header>
</template>

<style scoped></style>
