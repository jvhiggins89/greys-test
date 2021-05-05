<template>
  <div class="home">
    <HomeTopBanner></HomeTopBanner>
    <HomeTopCarousel></HomeTopCarousel>
    <HomeMiddleCards></HomeMiddleCards>

    
  </div>
</template>

<script>
// @ is an alias to /src
import HomeTopCarousel from '../components/HomeTopCarousel.vue'
import HomeTopBanner from '../components/HomeTopBanner.vue'
import HomeMiddleCards from '../components/HomeMiddleCards.vue'

export default {
  name: 'Home',
  components: {
    HomeTopCarousel,
    HomeTopBanner,
    HomeMiddleCards
  }
}
</script>
