<template>
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

