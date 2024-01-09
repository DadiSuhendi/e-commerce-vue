<script>
    // Import Swiper Vue.js components
    import { Swiper, SwiperSlide } from 'swiper/vue';

    // Import Swiper styles
    import 'swiper/css';

    import 'swiper/css/navigation';
    import 'swiper/css/pagination';

    // import required modules
    import { Navigation, Pagination, Mousewheel, Keyboard } from 'swiper/modules';

    export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        return {
        modules: [Navigation, Pagination, Mousewheel, Keyboard],
        };
    },
};
</script>

<template>
    <div class="pt-10">
    <div class="w-full h-96 overflow-hidden rounded-xl">
      <swiper
        :slidesPerView="'auto'"
        :cssMode="true"
        :loop="true"
        :pagination="{
          clickable: true,
        }"
        :navigation="true"
        :modules="modules"
        class="w-full h-full text-red-300"
      >
        <swiper-slide>
          <img src="https://plus.unsplash.com/premium_photo-1704546883637-0a759faf7871?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Hero Image 1">
        </swiper-slide>
        <swiper-slide>
          <img src="https://plus.unsplash.com/premium_photo-1675864663002-c330710c6ba0?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Hero Image 2">
        </swiper-slide>
        <swiper-slide>
          <img src="https://images.unsplash.com/photo-1704646526970-85f3a1d1a6da?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Hero Image 3">
        </swiper-slide>
      </swiper>
    </div>
  </div>
</template>