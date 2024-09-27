<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
<header class="flex items-center justify-between px-[45px] border-b-[2px] pb-[44px] pt-[45px]" >
  <div class="flex gap-[16px]">
    <img src="./assets/logo.svg" alt="">
    <div >
      <h2 class="font-bold text-[20px]">REACT SNEAKERS</h2>
      <p class="font-normal	text-[14px] text-[#9D9D9D]">Магазин лучших кроссовок</p>
    </div>
  </div>

  <div class="nav flex gap-[32px]">
     <div class="cart flex gap-[10px]">
      <img src="./assets/cart-logo.svg" alt="">
      <p>rub</p>
     </div>
     <div class="fav flex gap-[10px]">
      <img src="./assets/heart-logo.svg" alt="">
      <p>закладки</p>
     </div>
  </div>

  
</header>
  <!-- <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav> -->
  <RouterView />
</template>

<style scoped>
</style>
