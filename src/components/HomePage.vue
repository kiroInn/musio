<script setup lang="ts">

</script>

<template>
  <div class="wrapper">
    <!-- <img src="https://y.gtimg.cn/music/photo_new/T002R300x300M000003DFRzD192KKD.jpg" alt=""> -->
    <audio controls class="audio">
      <source src="http://ar.player.ra05.sycdn.kuwo.cn/3a2f9b2b2552c96b243da8dc242afaf6/64bddbef/resource/n2/320/0/68/1631030247.mp3?bitrate$320&format$mp3&source$kwplayer_ar_9.3.1.3_qq.apk&type$convert_url2&user$0?timestamp=1690164211304">
    </audio>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.audio {
  visibility: hidden;
  margin-top: 60px;
}
</style>