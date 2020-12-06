<template>
  <div class="container">
    <div id="app">
      <BannerB msg="BenimParametrem" />
      <Adres msg="BenimParametrem"/>
      <AktuelUrunler msg="BenimParametrem" />
      <!--  <UrunDetay msg="BenimParametrem"/> -->
      <!-- <KampanyalarB msg="BenimParametrem"/> -->
      <!-- <PromosyonKoduB msg="BenimParametrem"/> -->
      <!-- <GirisYapB msg="BenimParametrem"/> -->
      <!-- <Kategoriler msg="BenimParametrem"/> -->
      <!-- <BunlariKacirma msg="BenimParametrem"/> -->
      <!--  <Sepetim msg="BenimParametrem"/> -->
    </div>
  </div>
</template>

<script>
import BannerB from "@/components/BannerB.vue";
import UrunDetay from "@/components/UrunDetay.vue";
import Adres from "@/components/Adres.vue"
import AktuelUrunler from "@/components/AktuelUrunler.vue";
//import KampanyalarB from '@/components/KampanyalarB.vue'
//import PromosyonKoduB from '@/components/PromosyonKoduB.vue'
//import GirisYapB from '@/components/GirisYapB.vue'
//import Kategoriler from '@/components/Kategoriler.vue'
//import BunlariKacirma from '@/components/BunlariKacirma.vue'
//import Sepetim from '@/components/Sepetim.vue'

export default {
  name: "App",
  components: {
    BannerB,
    Adres,
    AktuelUrunler
    //UrunDetay
    //KampanyalarB
    //PromosyonKoduB
    //GirisYapB
    //Kategoriler
    //BunlariKacirma
    //Sepetim
  }
};
</script>

<style>
</style>
