<template>

    <v-card 
   color="#00acee"
   dark
 >
   <v-card-title >
     <v-icon 
       large
       left
     >
       mdi-twitter
     </v-icon>
     <span class="text-h6 font-weight-dark">Twitter</span>
   </v-card-title>

   <v-card-text class="text-h5 font-italic">
     "Always Forever Child"
   </v-card-text>

   <v-card-actions>
     <v-list-item class="grow">
       <v-list-item-avatar color="grey darken-3">
         <v-img
           class="elevation-6"
           alt=""
           src="https://studioghiblimovies.com/wp-content/uploads/2014/11/ponyo.png"
         ></v-img>
       </v-list-item-avatar>

       <v-list-item-content>
         <v-list-item-title>Iwasaka Hisei</v-list-item-title>
       </v-list-item-content>

       <v-row
         align="center"
         justify="end"
       >
         <v-icon class="mr-1">
           mdi-heart
         </v-icon>
         <span class="subheading mr-2">7.3k</span>
         <span class="mr-1">·</span>
         <v-icon class="mr-1">
           mdi-share-variant
         </v-icon>
         <span class="subheading">1.4k</span>
       </v-row>
     </v-list-item>
   </v-card-actions>
 </v-card>

</template>

<script>
   export default {
     data: () => ({
       //
     }),
   }
 </script>