<template>
  <div>
    <div class="alan1">
      <img src="../images/image1.jpg" />
      <v-btn class="buton1" depressed>Giriş Yap</v-btn>

      <v-btn class="buton2" depressed>Yeni Üyelik Oluştur</v-btn>
      <nuxt-link :to="'/Home/'">
        <p class="metin1">Giriş yapmadan devam et</p>
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.alan1 {
  width: 425px;
  height: 770px;
}
.alan1 img {
  width: 425px;
}

.buton1 {
  height: 50px !important;
  width: 380px;
  margin-left: 20px;
  margin-top: 40px;
  background-color: #05519f !important;
  color: white !important;
  font-family: Arial, Helvetica, sans-serif;
}
.buton2 {
  height: 50px !important;
  width: 380px;
  margin-left: 20px;
  margin-top: 20px;
  background-color: #33290a !important;
  color: white !important;
  font-family: Arial, Helvetica, sans-serif;
}
.metin1 {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  margin-top: 25px;
}
</style>