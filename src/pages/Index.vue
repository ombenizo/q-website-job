<template>
  <div class="q-pa-md">
    <q-carousel
      animated
      v-model="slide"
      navigation
      infinite
      :autoplay="autoplay"
      arrows
      transition-prev="slide-right"
      transition-next="slide-left"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
    >
      <q-carousel-slide
        :name="1"
        img-src="~assets/mountains.jpg"
        class="car-img"
      >
        <div class="absolute-center custom-caption">
          <div class="text-h2 text-white">First stop</div>
          <h6 class="animate__animated animate__bounce">Animation testing</h6>
          <div class="text-subtitle1 text-white">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            pariatur tempore error veniam aut similique nobis reiciendis
            perspiciatis molestiae minus esse, dicta repudiandae culpa possimus
            vel dolore ipsam! Quisquam, incidunt?
          </div>
        </div></q-carousel-slide
      >
      <q-carousel-slide
        :name="2"
        img-src="~assets/parallax1.jpg"
        class="car-img"
      >
        <div class="absolute-center custom-caption">
          <div class="text-h2 text-white">First stop</div>
          <div class="text-subtitle1 text-white">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            pariatur tempore error veniam aut similique nobis reiciendis
            perspiciatis molestiae minus esse, dicta repudiandae culpa possimus
            vel dolore ipsam! Quisquam, incidunt?
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide
        :name="3"
        img-src="~assets/parallax2.jpg"
        class="car-img"
      >
        <div class="absolute-center custom-caption">
          <div class="text-h2 text-white">First stop</div>

          <div class="text-subtitle1 text-white">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            pariatur tempore error veniam aut similique nobis reiciendis
            perspiciatis molestiae minus esse, dicta repudiandae culpa possimus
            vel dolore ipsam! Quisquam, incidunt?
          </div>
        </div>
      </q-carousel-slide>
      <q-carousel-slide :name="4" img-src="~assets/quasar.jpg" class="car-img">
      </q-carousel-slide>
      <q-carousel-slide :name="5" img-src="~assets/pexels-photo-11354823.jpeg">
        <div class="absolute-center custom-caption">
          <div class="text-h2 text-white">First stop</div>
          <div class="text-subtitle1 text-white">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt
            pariatur tempore error veniam aut similique nobis reiciendis
            perspiciatis molestiae minus esse, dicta repudiandae culpa possimus
            vel dolore ipsam! Quisquam, incidunt?
          </div>
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
  <div class="row">
    <div class="col">
      <div class="column items-center">
        <!-- Service-->
        <h2>Services</h2>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="col q-ma-md shadow-18 q-pa-md test">
      <div class="row">
        <div class="col-12 q-ma-none">
          <div class="column items-center">
            <q-icon name="web" size="100px" color="primary" class="icon" />
          </div>
        </div>
        <div class="col-12">
          <h6 class="q-mt-none q-mb-xs">Lorem ipsum dolor sit amet.</h6>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam harum
          laudantium, recusandae repellendus fugiat dolorem accusantium modi
          adipisci sequi consequuntur maxime inventore iusto doloribus alias
          deleniti tenetur! Natus asperiores illo laboriosam rem ad, recusandae
          esse! Animi architecto similique inventore odit eos dignissimos
          reiciendis accusamus officia, dolorem in doloremque excepturi aut.
        </div>
      </div>
    </div>
    <div class="col q-ma-md shadow-18 q-pa-md test">
      <div class="row">
        <div class="col-12 q-ma-none">
          <div class="column items-center">
            <q-icon name="domain" size="100px" color="primary" />
          </div>
        </div>
        <div class="col-12">
          <h6 class="q-mt-none q-mb-xs">Lorem ipsum dolor sit amet.</h6>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam harum
          laudantium, recusandae repellendus fugiat dolorem accusantium modi
          adipisci sequi consequuntur maxime inventore iusto doloribus alias
          deleniti tenetur! Natus asperiores illo laboriosam rem ad, recusandae
          esse! Animi architecto similique inventore odit eos dignissimos
          reiciendis accusamus officia, dolorem in doloremque excepturi aut.
        </div>
      </div>
    </div>
    <div class="col q-ma-md shadow-18 q-pa-md test">
      <div class="row">
        <div class="col-12 q-ma-none">
          <div class="column items-center">
            <q-icon name="devices" size="100px" color="primary" />
          </div>
        </div>
        <div class="col-12">
          <h6 class="q-mt-none q-mb-xs">Lorem ipsum dolor sit amet.</h6>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam harum
          laudantium, recusandae repellendus fugiat dolorem accusantium modi
          adipisci sequi consequuntur maxime inventore iusto doloribus alias
          deleniti tenetur! Natus asperiores illo laboriosam rem ad, recusandae
          esse! Animi architecto similique inventore odit eos dignissimos
          reiciendis accusamus officia, dolorem in doloremque excepturi aut.
        </div>
      </div>
    </div>
    <div class="col q-ma-md shadow-18 q-pa-md test">
      <div class="row">
        <div class="col-12 q-ma-none">
          <div class="column items-center">
            <q-icon name="computer" size="100px" color="primary" />
          </div>
        </div>
        <div class="col-12">
          <h6 class="q-mt-none q-mb-xs">Lorem ipsum dolor sit amet.</h6>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam harum
          laudantium, recusandae repellendus fugiat dolorem accusantium modi
          adipisci sequi consequuntur maxime inventore iusto doloribus alias
          deleniti tenetur! Natus asperiores illo laboriosam rem ad, recusandae
          esse! Animi architecto similique inventore odit eos dignissimos
          reiciendis accusamus officia, dolorem in doloremque excepturi aut.
        </div>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="col">
      <div class="column items-center">
        <h2>About</h2>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="col">
      <q-img src="~assets/mountains.jpg" />
    </div>
    <div class="col q-ml-md q-mt-none">
      <h1 class="q-mt-none">Lorem ipsum dolor sit.</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero voluptatibus corrupti quos harum modi molestias, nulla voluptatum est voluptas iusto eos nemo esse illum iure beatae praesentium illo quae enim minima sit blanditiis similique quam molestiae. Facere ratione optio repudiandae.</p>
    </div>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    const mouseE = ref(false);
    return {
      slide: ref(1),
      autoplay: ref(true),
    };
  },
};
</script>
<style>
.car-img {
  opacity: 0.7;
}
.animate__animated.animate__bounce {
  --animate-duration: 2s;
}
.animate__rotateIn {
  --animate-duration: 3s;
}
.test {
  transition: width 1s, height 1s, transform 1s;
  transition-timing-function: ease;
  cursor: pointer;
  
}
.test:hover {
  transform: scale(1.2, 1.2);
  background-color: aliceblue;
}
</style>