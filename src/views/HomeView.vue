<template>
  <div class="home mt-5 p-4">
    <h1 class="text-white font-bold text-lg md:text-xl mb-8">Here at Dent-Tec we offer an affordable professional service. Using the latest repair technology.</h1>
  <div class="w-full flex justify-center mt-10 p-5">
    <swiper
    class="swiper"
    :slides-per-view="1"
    :space-between="100"
    :loop="true"
    :autoplay="{
      delay: 4500,
      disableOnInteraction: false
    }"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
    :modules="modules"
    :breakpoints="{
      '640': {
        slidesPerView: 1,
        spaceBetween: 20
      },
      '768': {
        slidesPerView: 3,
        spaceBetween: 40
      },
      '1024': {
        slidesPerView: 4,
        spaceBetween: 50
      }
    }"
    navigation
  >
    <swiper-slide><img src="../assets/331312638_514117767557722_7753032014297735326_n.jpg" width="400" height="200" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/331321436_912508943281942_3245639952590270907_n.jpg" width="400" height="200" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/red1.jpeg" width="400" height="200" class="w-full" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/red2.jpeg" width="400" height="200" class="w-full" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/red3.jpeg" width="400" height="200" class="w-full" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/white1.jpeg" width="400" height="200" class="w-full" alt=""></swiper-slide>
    <swiper-slide><img src="../assets/white2.jpeg" width="400" height="200" class="w-full" alt=""></swiper-slide>
    
    ...
  </swiper>
  </div>

  <div class="mt-10 md:mt-28 mb-14 w-full flex justify-center items-center flex-col">
<h2 class="text-white text-center font-bold text-lg">What ever your vehicle, we can fix it!</h2>
    <p class="text-white p-4 w-full md:w-3/4">We are Nissan approved specialists. We take pride in the work we carry out in your vehicle as if it were our own. All manufacturers welcome.
    </p>
    <div class="flex flex-col md:flex-row justify-center items-center space-x-0 md:space-x-5 space-y-5 md:space-y-0 w-6/12 mt-6">
      <img src="../assets/nissan-icon.svg" width="80" height="80" alt="">
      <img src="../assets/ford-icon.svg" width="90" height="90" alt="">
      <img src="../assets/pngaaa.com-321047.png" width="110" height="80" alt="">
      <img src="../assets/renault.png" width="80" height="80" alt="">
      <img src="../assets/mits.png" width="80" height="80" alt="">
      <img src="../assets/suz.png" width="80" height="80" alt="">




    </div>
  </div>
</div>
</template>

<script>
// @ is an alias to /src
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';
  import { Autoplay, Navigation } from 'swiper'


  // Import Swiper styles
  import 'swiper/css';
  import 'swiper/css/navigation'


export default {
  name: 'HomeView',
  components: {
    Swiper,
      SwiperSlide,
  },
  setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };
      return {
        modules: [Autoplay, Navigation],
        onSwiper,
        onSlideChange,
      };
    },
}
</script>

<style scoped>
.home {
  background-color: #221B1B;

}
</style>
