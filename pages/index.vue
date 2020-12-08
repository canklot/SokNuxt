<template>
  <div class="container">
    <div id="app">
      <GirisYapB msg="BenimParametrem" />
      Counter:{{this.$store.state.store.kampanya1}}
      <button @click ="add_one">ben bir butonum </button>

    </div>
  </div>
</template>

<script>
import GirisYapB from "@/components/GirisYapB.vue";
import {mapState} from 'vuex';

/* giriş tuşunun düzeltilmesi lazım */

export default {
  name: "App",
  components: {
    GirisYapB
  },
  methods:{
    add_one(){
      this.$store.commit('store/increment')
    }
  }
};
</script>

<style>
</style>
