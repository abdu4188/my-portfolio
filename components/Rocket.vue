<template>
  <div class="svg-container">
    // eslint-disable-next-line vue/no-v-html
    <!-- <div v-html="RocketSvg" /> -->
    <img class="gif" style="border-radius: 25%" src="~/assets/g.gif" alt="">
  </div>
</template>

<script>
import RocketSvg from '~/assets/rocket.svg?raw'
export default {
  data () {
    return {
      RocketSvg
    }
  }
}
</script>

<style>
.svg-container {
  width: 80%;
  max-width: 400px;
  margin: 0 auto;
}
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {
    .gif {
      width: 90vw;
      margin-left: -16vw;
    }
  }
</style>
