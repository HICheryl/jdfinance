<template>
  <section class="swiper">
    <swiper :options="options">
      <swiper-slide>

      </swiper-slide>
    </swiper>
  </section>
</template>

<script>
import {swiper, swiperSlide} from 'vue-awesome-swiper'
export default {
  name: 'slider',
  props: {
    options: {
      type: Object,
      default () {
        return {
          loop:true
        }
      }
    }
  },
  components: {
    swiper,
    swiperSlider
  }
}
</script>

<style lang="css">
  @import "~";

</style>
