<script setup lang="ts">
import Card from '@/components/Card.vue'

defineProps({
  items: Array,
})

const onClickAdd = () => {
  alert('hello')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-10">
    <Card
      v-for="item in items"
      :key="item.id"
      :title="item.title"
      :imageUrl="item.imageUrl"
      :price="item.price"
      :isAdded="true"
      :isFavorite="true"
      :onClickAdd="onClickAdd"
    />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
</template>

<style scoped></style>
