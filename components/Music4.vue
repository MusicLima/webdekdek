<template>

    <v-card
      
    >
      <v-img
        src="https://studioghiblimovies.com/wp-content/uploads/2019/02/d78b1219f9991c69a7619d362548cb79f4d29e02_hq2.jpg"
        height="280px"
      ></v-img>
  
      <v-card-title>
        ジブリパークとジブリ展
      </v-card-title>
  
      <v-card-subtitle>
        Ghibli Studio
      </v-card-subtitle>
  
      <v-card-actions>
        <v-btn
          color="brown lighten-2"
          text
        >
        探検
        </v-btn>
  
        <v-spacer></v-spacer>
  
        <v-btn
          icon
          @click="show = !show"
        >
          <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
        </v-btn>
      </v-card-actions>
  
      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
  
          <v-card-text>
            制作現場を指揮する宮崎吾朗監督は「サツキとメイの家」や、「三鷹の森ジブリ美術館」等の建築物をてがけ、映画『ゲド戦記』『コクリコ坂から』『アーヤと魔女』などのアニメーション作品を生み出してきました。ジブリパークは本物のアニメーション世界を自分の足で歩き発見する場所。
            ひと足先にジブリパークを楽しめる展示が長野県でスタート。続いて、全国4会場にやってきます。
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>
  </template>

<script>
    export default {
      data: () => ({
        show: false,
      }),
    }
  </script>