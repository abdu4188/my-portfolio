<template>
  <div class="wrapper container text-center">
    <Rocket />
    <vue-typer
      :text="texts1"
      :repeat="0"
      :type-delay="100"
      :erase-on-complete="false"
    />
    <br>
    <vue-typer
      :pre-type-delay="3000"
      :text="texts2"
      :repeat="0"
      :type-delay="100"
      :erase-on-complete="false"
      class="second-text"
    />
    <Socials />
  </div>
</template>

<script>
import Rocket from '@/components/Rocket'
import Socials from '@/components/Socials'

export default {
  components: {
    Rocket,
    Socials
  },
  data () {
    return {
      texts1: [
        'Hello, My name is Abdulaziz'
      ],
      texts2: [
        'I create websites and apps.'
      ]
    }
  },
  methods: {}
}
</script>

<style lang="scss" >
.wrapper {
  width: 70vw;
}
.vue-typer .custom.char {
  font-family: monospace;
  color: white;
  font-size: 3.5rem;
}
.vue-typer .custom.caret {
  background-color: white;
}
.second-text .custom.char {
  color: white;
  font-size: 2rem !important;
}
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {
    .wrapper {
      width: 80vw;
    }
    .vue-typer .custom.char {
      font-size: 2rem;
    }
    .second-text .custom.char {
      font-size: 1rem !important;
    }
}
</style>
