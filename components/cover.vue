<template>
    <v-col col="12">
        <v-carousel
          cycle
          height="200"
          hide-delimiter-background
          show-arrows-on-hover
        >
          <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src">
          </v-carousel-item>
        </v-carousel>
        </v-col>
</template>

<script>
    
    export default {
      data() {
        return {
          items: [
            {
              src: "https://cdn.discordapp.com/attachments/955704380043186218/1017740061363687445/1.jpg",
            },
            {
              src: "https://cdn.discordapp.com/attachments/955704380043186218/1017740061627924511/2.jpg",
            },
            {
              src: "https://cdn.discordapp.com/attachments/955704380043186218/1017740061887959070/3.jpg",
            },
            {
              src: "https://cdn.discordapp.com/attachments/955704380043186218/1017740062194155570/4.jpg",
            },
            {
              src: "https://cdn.discordapp.com/attachments/955704380043186218/1017766592345554954/IMG_20220909_190027.jpg",
            },
            {
              src:"https://cdn.discordapp.com/attachments/955704380043186218/1018543379262492703/12.jpg",
            },
            {
              src:"https://cdn.discordapp.com/attachments/955704380043186218/1018544216030322718/13.jpg",
            },
            {
              src:"https://cdn.discordapp.com/attachments/955704380043186218/1018544889190957226/15.jpg",
            },
          ],
        };
      },
      
    };
    </script>