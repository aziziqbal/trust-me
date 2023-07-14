
<template>
  <div class="hero-banner flex items-center justify-center">
    <img src="~/assets/hero2.svg" class="img-hero" >
  </div>
</template>
<script lang="ts" setup></script>
<style lang="scss" scoped>

@font-face {
  font-family: "Djadoel";
  src: local("Djadoel"),
    url('../assets/djadoel.ttf') format("truetype");
}
@font-face {
  font-family: "Aspekta";
  src: local("Aspekta"),
    url('../assets/aspekta.ttf') format("truetype");
}
.hero-banner {
  bottom: 0;
  left: 0;
  position: absolute;
  right: 0;
  top: 0;
  mask-image: url('../assets/header-mask.png');
  mask-position: center top;
  mask-repeat: no-repeat;
  mask-size: 100% 100%;
  .img-hero {
    height:100vh;
    width: 100%;
    position: absolute;
    top:88px;
    object-fit: cover;
  }
}
</style>
