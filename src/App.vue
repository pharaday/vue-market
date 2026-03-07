<script setup>
import Header from '@/components/Header.vue'
import CardList from '@/components/CardList.vue'
import Drawer from '@/components/Drawer.vue'
</script>

<template>
<!--  <Drawer />-->

  <div class="w-4/5 mt-15 m-auto bg-white rounded-2xl shadow-2xl">
    <Header />

    <div class="p-10">
      <div class="flex justify-between items-center mb-8">
        <h2 class="text-3xl font-bold">Все кроссовки</h2>

        <div class="flex gap-4">
          <select class="border border-slate-200 focus:border-slate-400 rounded-2xl outline-none py-3 px-4">
            <option value="">По названию</option>
            <option value="">По цене (дешевле)</option>
            <option value="">По цене (дороже)</option>
          </select>


          <div class="relative">
            <img class="absolute top-4 left-3" src="/search.svg" alt="">
            <input class="border border-slate-200 focus:border-slate-400 rounded-2xl outline-none py-3 pl-8 pr-4" type="text" placeholder="Поиск...">
          </div>
        </div>
      </div>

      <CardList />
    </div>
  </div>

  <Test />
</template>

<style scoped></style>
