<script setup lang="ts">
// import TheWelcome from '../components/TheWelcome.vue'
import WelcomeBanner from '../components/banner/WelcomeBanner.vue'
import Layanan from '../components/layanan/Layanan.vue'
</script>

<template>
  <div class="container d-flex flex-column justify-content-center">
    <div class="contaier d-flex flex-row w-100 justify-content-center align-items-center" id="welcome">
      <WelcomeBanner />
    </div>
    <div class="container layanan">
      <Layanan />
    </div>    
  </div>
</template>


<style scoped>
#welcome {
  column-gap: 50px;
  margin-bottom: 100px;
}
</style>
