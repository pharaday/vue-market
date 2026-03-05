<script setup lang="ts">
import Card from '@/components/Card.vue'

const onClickAdd = () => {
  alert('hello')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-10">
    <Card title="Мужские Кроссовки Nike Blazer Mid Suede"
          imageUrl="/sneakers/sneakers-1.jpg"
          :price="1205"
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
