<template>
  <div class="home mt-5">
    <h1 class="text-white font-bold text-lg md:text-4xl p-2">
      Your specialists in vehicle accident repair
    </h1>
    <h1 class="text-white font-bold text-lg md:text-xl mb-14 p-2">
      Here at Dent-Tec we offer an affordable professional service. Using the
      latest repair technology.
    </h1>
    <div class="
            flex flex-col
            lg:flex-row
            justify-center
            items-center
            space-x-0
            lg:space-x-5
            space-y-5
            lg:space-y-0
            mt-6
            w-full
          ">
      <img src="../assets/nissan-icon.svg" width="80" height="80" alt="" />
      <img src="../assets/ford-icon.svg" width="90" height="90" alt="" />
      <img src="../assets/pngaaa.com-321047.png" width="110" height="80" alt="" />
      <img src="../assets/renault.png" width="80" height="80" alt="" />
      <img src="../assets/mits.png" width="80" height="80" alt="" />
      <img src="../assets/suz.png" width="80" height="80" alt="" />
      <img src="../assets/iconfinderbmwlogo4140436-115966_115915.svg" width="80" height="80" alt="" />
      <img src="../assets/iconfindercitroenlogo4143278-115962_115920.svg" width="80" height="80" alt="" />
      <img src="../assets/iconfinderminilogo4141777-115959_115922.svg" width="80" height="80" alt="" />
      <img src="../assets/mercedes_benz_logo_icon_145798.svg" class="bg-white" width="80" height="80" alt="" />

    </div>


    <div class="
          mt-10
          md:mt-28
          mb-14
          w-full
          flex
          justify-center
          items-center
          flex-col
        ">
      <h2 class="text-white text-center font-bold text-xl p-2">
        What ever your vehicle, we can fix it!
      </h2>
      <p class="text-white">specialists manufacturers welcome</p>
      <p class="text-white p-4 text-xl w-full md:w-3/4 my-28">
        We are Nissan approved specialists. We take pride in the work we carry
        out in your vehicle as if it were our own. All manufacturers welcome.
      </p>


    </div>
    <div class="text-white text-center text-xl mb-10">
      Take a look at some of our latest repairs on <a
        href="https://www.facebook.com/people/Dent-Tec/100087966960493/?fref=nf" target="_blank"
        class="text-blue-600">Facebook</a>
    </div>

    <div
      class="flex flex-col lg:flex-row w-full justify-center items-center mt-5 mb-10 space-y-5 lg:space-y-0 space-x-0 lg:space-x-4">

      <div>
        <iframe
          src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fpermalink.php%3Fstory_fbid%3Dpfbid02Z9DAUDV46BoHD6y66ncEr9aR676tS6dTxgtKqwfdmSSHxpt9kD4AxVi4pkYUNnejl%26id%3D100087966960493&show_text=true&width=500"
          width="500" height="601" style="border:none;overflow:hidden" scrolling="yes" frameborder="0"
          allowfullscreen="true"
          allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
      </div>
      <div>
        <iframe
          src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fpermalink.php%3Fstory_fbid%3Dpfbid02bduz7z9Y28ah8zyD2bHSjFnZJnrXLeiVBcm7mZh7MyuGGhm3U3ukzkvVJAbpDSTNl%26id%3D100087966960493&show_text=true&width=500"
          width="500" height="645" style="border:none;overflow:hidden" scrolling="yes" frameborder="0"
          allowfullscreen="true"
          allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
      </div>
    </div>

    <div class="my-28">
      <div class="p-2">
        <p class="text-white text-2xl">Can I choose who repairs my car after an accident?</p>
        <p class="text-white text-lg">YES! It’s your car, your choice! You are free to choose who repairs your car after a
          road traffic collision.</p>
        <p class="text-white text-lg">Click <a class="bg-white rounded-lg text-black px-2"
            href="https://www.crashservices.com/can-i-choose-who-repairs-my-car-after-an-accident/"
            target="_blank">here</a> to find out more!</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay, Navigation } from "swiper";

// Import Swiper styles
import "swiper/css";
import "swiper/css/navigation";

export default {
  name: "HomeView",
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log("slide change");
    };
    return {
      modules: [Autoplay, Navigation],
      onSwiper,
      onSlideChange,
    };
  },
};
</script>

<style scoped>
.home {
  background-color: #221b1b;
}

swiper-slide {
  height: 100% !important;
}

@media only screen and (max-width: 600px) {
  iframe {
    width: 100% !important;
  }
}</style>
