<template>
  <div class="bubble-photo" data-aos="fade-in">
    <div class="img" :style="{ backgroundImage: `url(` + require(`~/assets/img/${img}`) + `)` }">
      <div class="bubble bubble__one"></div>
      <div class="bubble bubble__two"></div>
      <div class="bubble bubble__three"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    img: String,
  },
};
</script>