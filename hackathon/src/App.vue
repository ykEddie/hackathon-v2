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
  <TheNavBar />
  <SocialMedia />
  <TheFooter />
  
 
</template>

<script>
import TheNavBar from './components/layout/TheNavBar.vue'
import TheFooter from './components/layout/TheFooter.vue'
import SocialMedia from './components/SocialMedia.vue'
export default {
  name: 'App',
  components: {
    TheNavBar, TheFooter, SocialMedia
  }
}
</script>

