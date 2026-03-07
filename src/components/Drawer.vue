<script setup lang="ts">
import DrawerHead from '@/components/DrawerHead.vue'
import CartItemList from '@/components/CartItemList.vue'
</script>

<template>
  <div class="fixed top-0 left-0 w-full h-full bg-black z-10 opacity-70"></div>

  <div class="bg-white w-96 h-full z-20 fixed right-0 top-0 p-8">
    <DrawerHead />
    <CartItemList />

    <div class="flex flex-col gap-4 mb-5">
      <div class="flex gap-2">
        <span>Итого: </span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12 999 $</b>
      </div>

      <div class="flex gap-2">
        <span>Налог 5%: </span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>1074 $</b>
      </div>

      <button
        disabled=""
        class="bg-lime-500 w-full rounded-2xl py-2 text-white hover:bg-lime-600 transition active:scale-95 cursor-pointer disabled:opacity-50"
      >
        Оформить заказ
      </button>
    </div>
  </div>
</template>

<style scoped></style>
