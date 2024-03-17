<script setup>
import MyHello from './components/MyHello.vue'
</script>

<template>
  <div class="mb-2 text-slate-700">
    <MyHello title="new balance" :price="11000" :isAdded="true"> </MyHello>
  </div>
</template>
