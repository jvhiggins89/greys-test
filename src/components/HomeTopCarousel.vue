<template>
  <div id=carouselDiv>
    <b-carousel
      id="carousel-1"
      :interval="50000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="240"
      style="text-shadow: 1px 1px 2px #333;"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="Create your dream garden"
        img-src="../assets/garden.jpg"
      >
      </b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="../assets/Tulips.jpg">
      </b-carousel-slide>

    </b-carousel>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap");
.h1, h1 {
    font-size: 3rem;
    font-family: 'Amatic SC', cursive;
    font-weight: 900;
    text-shadow: 2px 2px 4px #000000;
}

.carousel-caption {
    top:50%;
    transform: translateY(-50%);
    bottom:initial;
    color: #fff;
    text-align: center;
    font-size: 3rem;
    font-family: 'Amatic SC', cursive;
    font-weight: 900;
    text-shadow: 2px 2px 4px #000000;
}

</style>