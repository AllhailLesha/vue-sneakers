<script setup>
const props = defineProps({
  title: String,
  price: Number,
  isAdded: Boolean
})

</script>

<template>
  <div class="product">
    <h2>Товар: {{ title }}</h2>
    <h3>Цена: {{ price }}</h3>
    <h4>Добавлен: {{ isAdded }}</h4>

    <slot></slot>
  </div>
</template>

<style scope>
.product {
  border: 1px solid teal;
  padding: 10px;
  margin: 10px;
}
</style>
