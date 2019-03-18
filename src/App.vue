<template>
  <div id="app">
    <div class="middle">
      <div class="bg-cont"></div>
      <section>
        <h2>YENİLENDİK, DAHA GÜÇLÜ GELİYORUZ.</h2>
        <div class="flexer"></div>
        <h2 class="ra-t">Yeni İletişim Bilgileri</h2>
        <div class="icon-info">
          <img src="./assets/mail.png" alt="mailico" height="40">
          <div></div>
          <span>info@eroka.com.tr</span>
        </div>
        <div class="icon-info">
          <img src="./assets/telefon.png" alt="mailico" height="40">
          <div></div>
          <span>+90 (531) 274 13 38</span>
        </div>
        <div class="icon-info">
          <img src="./assets/yer.png" alt="mailico" height="40">
          <div></div>
          <span>Melih Gökçek Bulvarı, Arıkanlar Grand Plaza, No: 138/40 Yenimahalle/ANKARA</span>
        </div>
      </section>
      <div class="flexer"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700');
body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Montserrat', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000;
  display: flex;
  background-color: #051c48;
  width: 100vw;
  align-items: center;
  justify-content: center;
  height: 100vh;
  margin: 0;
  padding: 0;
}
.icon-info {
  display: flex;
  font-size: 16px;
  align-self: stretch;
  align-items: center;
  text-align: left;
  margin: 5px 0px;
}
.icon-info > div {
  margin: 0px 4px;
}
section {
  display: flex; flex-direction: column;
  align-items: center;
  width: 80%; flex: 4;
}
section > h2 {
  font-weight: 600; font-size: 19px;
}
.flexer {
  flex: 1;
}
.ra-t {
  align-self: stretch; text-align: right; border-bottom: 5px solid #ddab47; padding-bottom: 10px;
}
.bg-cont {
  width: 100%;
  background-position: center;
  background-size: 160px auto;
  background-image:url('./assets/logo.png');
  background-repeat: no-repeat;
  flex: 3;
  display: flex;
}
.middle {
  display: flex;
  flex-direction: column;
  width: 95%;
  height: 95%;
  max-width: 500px;
  padding: 15px;
  max-height: 700px;
  align-items: center;
  background-color: #fff;
  box-shadow: 8px 8px 15px 8px rgba(0,0,0, .6);
}
</style>
