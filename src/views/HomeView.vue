<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Navigation, Pagination, A11y } from "swiper/modules";
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";
</script>

<template>
  <Swiper
    :modules="[Navigation, Pagination]"
    :slides-per-view="1"
    :space-between="50"
    :pagination="{ clickable: true }"
  >
    <SwiperSlide>
      <img src="../assets/frog.png" alt="" />
    </SwiperSlide>
    <SwiperSlide>
      <img src="../assets/frog.png" alt="" />
    </SwiperSlide>
    <SwiperSlide>
      <img src="../assets/frog.png" alt="" />
    </SwiperSlide>
  </Swiper>

  <div class="flex justify-between mx-[60px] items-center mt-[40px]">
    <p>Все кроссовки</p>
    <div class="flex">
        <img src="../assets/search.svg" alt="">
        <input type="text" class="border-[#F3F3F3] border-t-[45px] placeholder">
    </div>
  </div>

  <div class="mt-[30px] flex flex-wrap gap-[25px]">
    <div class="">
      <img src="../assets/nike-1.png" alt="" />
      <p>Мужские Кроссовки Nike Blazer Mid Suede</p>
      <div class="flex items-center	">
        <div>
          <p>Цена:</p>
          <p>12 999</p>
        </div>
        <img src="../assets/Vector.svg" alt="" />
      </div>
    </div>
  </div>
</template>
