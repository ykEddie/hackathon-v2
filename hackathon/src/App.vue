<template>
  <div>
    <BaseCard />
    <BaseCardImage :cardInfo="cardInfo" :img="CardImage" />
  </div>
</template>

<script setup>
import BaseCard from "./components/BaseCard.vue";
import BaseCardImage from "./components/BaseCardImage.vue";

const cardInfo = {
  cardTitle: "NEW ARRIVALS",
};
const CardImage = {
  url: "https://empireave.com/wp-content/uploads/2020/02/Stussy-SP20-Lookbook-D2-Mens-17.jpg",
  alt: "One new product from stussy",
};
</script>
