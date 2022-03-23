<template>
  <div class="w-80">
    <img :src="props.img.url" :alt="props.img.alt" />
    <h1>{{ props.cardInfo.cardTitle }}</h1>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  cardInfo: {
    type: Object,
  },
  img: {
    type: Object,
  },
});
</script>
