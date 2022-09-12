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
     "Keep in mind"
   </v-card-text>

   <v-card-actions>
     <v-list-item class="grow">
       <v-list-item-avatar color="grey darken-3">
         <v-img
           class="elevation-6"
           alt=""
           src="https://studioghiblimovies.com/wp-content/uploads/2014/12/my-neighbour-totoro-studio-ghibli-3010694-1920x1200.jpg"
         ></v-img>
       </v-list-item-avatar>

       <v-list-item-content>
         <v-list-item-title>Gemma Chan</v-list-item-title>
       </v-list-item-content>

       <v-row
         align="center"
         justify="end"
       >
         <v-icon class="mr-1">
           mdi-heart
         </v-icon>
         <span class="subheading mr-2">25.6k</span>
         <span class="mr-1">·</span>
         <v-icon class="mr-1">
           mdi-share-variant
         </v-icon>
         <span class="subheading">8.9k</span>
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