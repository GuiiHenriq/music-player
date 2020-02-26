<template>
  <div class="app">
    <div id="audio" class="player-wrapper">
      <audio-player></audio-player>
    </div>
  </div>
</template>

<script>
import AudioPlayer from "./AudioPlayer.vue";

export default {
  name: "Player",
  components: {
    AudioPlayer
  }
  //https://upload.wikimedia.org/wikipedia/commons/d/d6/Louis-Emmanuel_Jadin_-_Nocturne_No._3_in_G_minor_-_2._Allegro_molto.ogg
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss"></style>
