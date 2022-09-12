<template>

    <v-card
      
    >
      <v-img
        src="https://studioghiblimovies.com/wp-content/uploads/2019/03/laputa_robot_by_panda_neko_pyon_d9awbhb-fullview1.jpg"
        height="280px"
      ></v-img>
  
      <v-card-title>
        ジブリの大博覧会
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
            スタジオジブリの設立から約30年間の歩みを体感できる特別企画。「風の谷のナウシカ」から「思い出のマーニー」まで、これまでのジブリ作品がどのように生み出され、世に出て行ったのか。会場では当時を振り返るポスターやチラシといった広告宣伝物を中心に、制作資料、企画書など未公開のものを含む膨大な数の資料が所狭しと展示空間を圧倒します。
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