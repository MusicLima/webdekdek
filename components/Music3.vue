<template>

    <v-card
      
    >
      <v-img
        src="https://studioghiblimovies.com/wp-content/uploads/2020/03/73-737065_living-waters-ag-wave-vector-clipart.png"
        height="280px"
      ></v-img>
  
      <v-card-title>
        アニメージュとジブリ展
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
            本展覧会は1978年の創刊当時から80年代の雑誌「アニメージュ」（徳間書店）に焦点を当てました。まだアニメという言葉さえ広がっていない時代から、1979年に登場した「機動戦士ガンダム」の大ヒットによりアニメが大きく飛躍するブーム期。そして、鈴木敏夫が後のジブリにつながる高畑勲・宮崎駿両監督を見出し、「風の谷のナウシカ」「天空の城ラピュタ」の映画製作に傾倒するまでの道のりを紹介します。
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