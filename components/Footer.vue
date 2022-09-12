<template>
    <v-footer padless>
      <v-card color="FECD70" class="flex" flat tile>
        <v-card-title class="dark">
          <v-spacer></v-spacer>
          <Italic class="brown--text">
            Get connected with me more on social networks!...
          </Italic>
  
          <v-btn class="mx-4" dark icon>
            <a
              style="color: skyblue"
              href="https://www.facebook.com/musey.quinzel.1"
              target="_blank"
              rel="noopener noreferrer"
            >
              <v-icon size="24px"> mdi-facebook </v-icon>
            </a>
          </v-btn>
  
          <v-btn class="mx-4" light icon>
            <a
              style="color: orange"
              href="https://gitlab.com/6431503041"
              target="_blank"
              rel="noopener noreferrer"
            >
              <v-icon size="24px"> mdi-gitlab </v-icon>
            </a>
          </v-btn>
  
          <v-btn class="mx-4" light icon>
            <a
              style="color: white"
              href="https://github.com/MusicLima"
              target="_blank"
              rel="noopener noreferrer"
            >
              <v-icon size="24px"> mdi-github </v-icon>
            </a>
          </v-btn>
  
          <v-btn class="mx-4" dark icon>
            <a
              style="color: plum"
              href="https://www.instagram.com/thejourneyofmusic_inmfu/"
              target="_blank"
              rel="noopener noreferrer"
            >
              <v-icon size="24px"> mdi-instagram </v-icon>
            </a>
          </v-btn>
        </v-card-title>
  
        <v-card-text class="py-2 brown--text text-center">
          {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
        </v-card-text>
      </v-card>
    </v-footer>
  </template>
  
    <script>
  export default {
    data: () => ({
      icons: ["mdi-facebook", "mdi-gitlab", "mdi-github", "mdi-instagram"],
    }),
  };
  </script>
  
  <style >
  a {
    all: unset;
  }
  </style>