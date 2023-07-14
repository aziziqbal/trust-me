<template>
  <div class="container-trust">
    <div class="header-menu flex items-center justify-center">
      <img src="https://www.primeskills.id/wp-content/uploads/2021/11/logo-02.png" class="img-logo" >
      <div class="nav-menu flex items-center justify-center">
        <div class="text-menu">
          HOME
        </div>
        <div class="text-menu">
          SUMMARY
        </div>
        <div class="text-menu">
          PROMINENT UNIQUE
        </div>
        <div class="text-menu">
          GETTING STARTED
        </div>
        <div class="text-menu">
          HOW TO BUY
        </div>
      </div>
    </div>
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
.container-trust {
  .header-menu {
    height: 90px;
    width:100%;
    background: #3169B1;
    .img-logo {
      position: absolute;
      top:10px;
      width:170px;
      cursor: pointer;
    }
    .nav-menu {
      background:#9EC96B;
      height:60px;
      padding-left: 30px;
      padding-right: 30px;
      border-radius: 10px;
      position: absolute;
      top:65px;
      gap:30px;
      .text-menu {
        font-family: 'Djadoel';
        cursor: pointer;
        color:white;
        font-size: 20px;
      }
      .text-menu:hover {
        text-decoration: underline;
      }
    }
  }
}

</style>
