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
    <div class="hero-con flex items-center justify-center">
      <Header />
      <div class="card-summary flex flex-row">
        <div class="left-side flex items-center flex-col">
          <div class="title-1">
            HAVE YOUR EVER BEEN...
          </div>
          <div class="title-2">
            in a situation where you didn't understand
          other people's conversations and needed to
          comprehend what they were talking about?
          You have to answer quickly!
          </div>
        </div>
        <div class="right-side flex items-center flex-col">
          <div class="title-youtube">
            WATCH THE TRAILER
          </div>
          <div class="box-youtube">

          </div>
        </div>
      </div>
    </div>
    <div class="section-2 flex items-center justify-center flex-row">
      <img src="~/assets/sec2.svg" class="img-sec" >
      <div class="right-side2">
        <div class="tit2">
          Game Summary
        </div>
        <div class="desc2">
          
Game ini bergenre casual dan edukatif yang sangat mudah dimainkan. Inti dari permainan ini adalah mengembangkan keterampilan komunikasi. Kamu akan berada dalam situasi di mana kamu harus berkomunikasi dengan benar dalam percakapan atau konteks pembicaraan. 
Selain itu, kamu akan mendapatkan kepercayaan lebih dari lawan bicaramu. Menemukan berbagai cerita seru membuat game ini sangat menyenangkan untuk dimainkan. Gunakan game ini sebagai sarana untuk mengembangkan keterampilan komunikasimu.
        </div>
      </div>
    </div>
    <div class="section-3 flex items-center justify-start flex-col">
      <div class="flex items-center justify-center flex-row">
        <div class="card-1 flex flex-col items-end justify-center " style="position:relative">
          <img src="~/assets/sec1.png" style="position:absolute;left:-30px;" >
          <div class="card2 flex items-center justify-center">
            single
          </div>
          <div class="card2 flex items-center justify-center">
            Multiplayer
          </div>
        </div>
        <div class="card-3 flex flex-col items-center justify-center">
          <div class="title-card3 mb-4">
            You can play using the platform...
          </div>
          <div class="flex items-center jutify-center flex-row" style="margin-top:20px;">
            <img src="~/assets/asd.png" >
          </div>
        </div>
      </div>
      <img src="~/assets/assprom.png" >
    </div>
    <img src="~/assets/web-01.svg" style="width:100%" >
    <img src="~/assets/web-02.svg" style="width:100%" >
    <img src="~/assets/web-03.svg" style="width:100%" >
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
      z-index:3;
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
  .hero-con {
    background: url('../assets/bg.svg');
    background-repeat: no-repeat;
    background-size: cover;
    height:105vh;
    width:100%;
    .card-summary {
      position: absolute;
      z-index: 1;
      bottom:-50px;
      background:#9EC96B;
      width:800px;
      height:300px;
      border-radius: 30px;
      padding:20px;
      .left-side {
        margin-right: 40px;
        .title-1 {
          font-family: 'Djadoel';
          color:white;
          font-size: 35px;
          margin-bottom:10px;
        }
        .title-2 {
          font-family: 'Aspekta';
          color:white;
          font-size: 18px;
          text-align: center;
        }
      }
      .right-side {
        height:300px;
        .title-youtube {
          background: #51cdf4;
          padding-left: 20px;
          padding-right:20px;
          padding-top:5px;
          border-top-left-radius: 10px;
          border-top-right-radius: 10px;
          font-family: 'Djadoel';
          color:white;
          font-size: 20px;
        }
        .box-youtube {
          width:300px;
          height:200px;
          border:10px solid white;
        }

      }
    }
  }
  .section-2 {
    background: #ffce6c;
    height:100%;
    padding-top:40px;
    padding-bottom:40px;
    width: 100%;
    .img-sec {
      width:400px;
    }
    .right-side2 {
      margin-left:50px;
      width:500px;
      .tit2 {
        font-family: 'Djadoel';
        color:black;
        font-size: 30px;
      }
      .desc2 {
        margin-top:20px;
        font-family: 'Aspekta';
        color:black;
        font-size: 18px;

      }
    }
  }
  .section-3 {
    background: url('../assets/bg.svg');
    background-repeat: no-repeat;
    background-size: cover;
    height:100%;
    width:100%;
    padding-top:30px;
    padding-bottom:30px;
    .card-1 {
      padding-top:30px;
      padding-bottom:30px;
      height:300px;
      padding-right:30px;
      height:100%;
      width:500px;
      border:10px solid #ffce6c;
      margin-right:20px;
      border-radius: 10px;
      background: white;
      .card2 {
        height:50px;
        width:200px;
        background: #be893d;
        border-radius: 10px;
        color:white;
        margin-bottom: 10px;
        font-family: 'Djadoel';
        color:white;
        font-size: 20px;
      }
    }
    .card-3 {
      background: #d7656a;
      width:500px;
      height:300px;
      border-radius: 10px;
      .title-card3 {
        font-family: 'Djadoel';
        color:white;
        font-size: 20px;
      }
    }
  }
}

</style>
