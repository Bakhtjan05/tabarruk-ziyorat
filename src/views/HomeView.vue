<template>
  <div class="main-box">
    <Header/>
    <Hero/>
  </div>
</template>
<script setup lang="ts">
import Header from "@/components/Header.vue"
import Hero from "@/components/Hero.vue"
</script>

<style scoped>
    .main-box {
      width: 100%;
      height: 100vh;
      background-image:
      linear-gradient(180deg, #07091C -4.12%, rgba(7, 9, 28, 0.60) 49.39%, rgba(7, 9, 28, 0.20) 85.78%, #07091C 100%),
       url(../assets/images/main-page-photo.png);
      background-repeat: no-repeat;
      background-size: cover;
      
;
      
    }

    
</style>