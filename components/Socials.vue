<template>
  <div class="social-wrapper container text-center">
    <div>
      <v-btn icon href="https://github.com/abdu4188" target="_blank">
        <v-icon>mdi-github</v-icon>
      </v-btn>
      <v-btn icon href="https://www.linkedin.com/in/abdulaziz-yesuf-74a664178/" target="_blank">
        <v-icon>mdi-linkedin</v-icon>
      </v-btn>
      <v-btn icon href="mailto:abdulazizyesuf7@gmail.com" target="_blank">
        <v-icon>mdi-gmail</v-icon>
      </v-btn>
      <v-btn icon href="https://twitter.com/youngg_simbba" target="_blank">
        <v-icon>mdi-twitter</v-icon>
      </v-btn>
      <v-btn icon href="https://t.me/A6du2" target="_blank">
        <v-icon>mdi-telegram</v-icon>
      </v-btn>
      <v-btn icon href="tel:+251941889238" target="_blank">
        <v-icon>mdi-phone</v-icon>
      </v-btn>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.social-wrapper {
  display: flex;
  width: 30vw;
  margin-top: 10vh;
}
.v-btn .v-icon {
  font-size: 2rem !important;
  color: white !important;
}
.v-btn .v-icon:hover {
  font-size: 2rem !important;
  color: greenyellow !important;
}
.v-btn {
  margin-right: 1vw;
}
@media only screen
  and (min-device-width: 320px)
  and (max-device-width: 480px)
  and (-webkit-min-device-pixel-ratio: 2) {
    .social-wrapper {
      width: 80vw;
    }
  }
</style>
