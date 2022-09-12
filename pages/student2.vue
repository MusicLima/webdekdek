<template>
    <v-row>
        <Footintro/>
      <v-col col="12">
        <v-carousel
          cycle
          height="550"
          hide-delimiter-background
          show-arrows-on-hover
        >
          <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src">
          </v-carousel-item>
        </v-carousel>
  
        <v-col class="py-4 d-flex flex-wrap" col="12" md="12">
          <v-col col="4" md="3">
            <v-col>
              <Music />
            </v-col>
  
            <v-col>
              <Music2 />
            </v-col>
          </v-col>
  
          <v-col col="7" md="3">
            <Music3 />
          </v-col>
  
          <v-col col="7" md="3">
            <Music4 />
          </v-col>
  
          <v-col col="7" md="3">
            <Music5 />
          </v-col>
  
          <v-col col="12" md="6">
            <iframe
              style="width: 100%; height: 460px"
              src="https://www.youtube-nocookie.com/embed/hpfLKbjTWn0"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            >
            </iframe>
          </v-col>
  
          <v-col col="12" md="6">
            <iframe
              style="width: 100%; height: 460px"
              src="https://www.youtube-nocookie.com/embed/ByXuk9QqQkk"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            >
            </iframe>
          </v-col>
        </v-col>
      </v-col>
  
      <v-col>
        <Footer />
      </v-col>
  
    </v-row>
  </template>
  
  
  
  
  <script>
  import Music3 from "~/components/Music3.vue";
import Footintro from "~/components/footintro.vue";
  export default {
    data() {
      return {
        items: [
          {
            src: "https://studioghiblimovies.com/wp-content/uploads/2016/01/YorAldG-studio-ghibli-wallpapers.jpg",
          },
          {
            src: "https://studioghiblimovies.com/wp-content/uploads/2016/01/d6tejZf-studio-ghibli-wallpaper.jpg",
          },
          {
            src: "https://studioghiblimovies.com/wp-content/uploads/2016/01/AnYp3Wd-studio-ghibli-wallpaper.jpg",
          },
          {
            src: "https://studioghiblimovies.com/wp-content/uploads/2014/12/catbuswp.jpg",
          },
          {
            src: "https://studioghiblimovies.com/wp-content/uploads/2019/02/44019.jpg",
          },
          {
            src:"https://studioghiblimovies.com/wp-content/uploads/2018/06/31347300_2138391272842659_3544354433116667904_n.jpg",
          },
          {
            src:"https://studioghiblimovies.com/wp-content/uploads/2020/10/0f20a1a13a64ee899a6a7410abeeab81c2fa483c.jpg",
          },
          {
            src:"https://www.thisiscolossal.com/wp-content/uploads/2020/09/ghibli-5.jpg",
          },
        ],
      };
    },
    components: { Music3, Footintro },
  };
  </script>