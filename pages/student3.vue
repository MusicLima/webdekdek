<template>
    
  <v-responsive
    class="overflow-y-auto"
    max-height="600"
  >
    <div class="pa-10 text-center">
      LADA YODPHOSRI 6431503050
      </div>
    
      <v-carousel hide-delimiters>
  <v-carousel-item
    v-for="(item,i) in items"
    :key="i"
    :src="item.src"
    
    
    
  ></v-carousel-item>
</v-carousel>

      <v-container>
        <v-row dense>
          <v-col cols="12">
            <v-img
              height="350"
              src="https://img.apmcdn.org/e57270ef1f77a2453f4605fb953f8726b67a68f2/uncropped/540971-20151217-the-1975.jpg"
            >
           <div class="text-center">
              The 1975 - I'm In Love With You
           </div> 
           <v-card-actions>
                <v-btn text>
                  <a
                    style="text-decoration: none; color: aliceblue"
                    href="https://www.youtube.com/watch?v=UVzVUDXoi0Y"
                    target="_blank"
                    rel="noopener noreferrer"
                    
          <v-icon>mdi-play-circle-outline </v-icon>
          
                    listen</a>
                </v-btn>
              </v-card-actions>

          </v-img>
          </v-col>
        </v-row>
    </v-container>

    <v-container>
      <v-row dense>
          <v-col cols="12">
            <v-img
              height="350"
              src="https://www.aelitaxtranslate.com/wp-content/uploads/2016/01/the-1975-robbers.jpg"
            >
           <div class="text-center">
              The 1975 - Robbers 
           </div> 
           <v-card-actions>
                <v-btn text>
                  <a
                    style="text-decoration: none; color: aliceblue"
                    href="https://www.youtube.com/watch?v=Iyy3YOpxL2k&list=RDEMqNiADTQ6W7zFH3lMugz3Vg&start_radio=1&rv=UVzVUDXoi0Y"
                    target="_blank"
                    rel="noopener noreferrer"
                    
          <v-icon>mdi-play-circle-outline </v-icon>
          
                    Listen</a>
                </v-btn>
              </v-card-actions>

          </v-img>
          </v-col>
        </v-row>
    </v-container>


    <v-responsive
      height="150vh"
      class="text-center pa-2">

      <v-responsive min-height="20vh"></v-responsive>
      <div class="text-center text-body-2 mb-12">
        THE PICTURE I LIKE
      </div>
      <v-container>
      <v-row dense>
          <v-col cols="4">
            <v-img
              height="350"
              src="https://i.pinimg.com/564x/fa/64/ae/fa64ae9ee69e8a8639aaa6cc87edf751.jpg"
            >
           <div class="text-center">
              Sea 
           </div> 
           <v-card-actions>
                <v-btn text>
                  <a
                    style="text-decoration: none; color: aliceblue"
                    href="https://www.pinterest.com/search/pins/?q=sea&rs=typed"
                    target="_blank"
                    rel="noopener noreferrer"
                    >View</a>
                </v-btn>
              </v-card-actions>

          </v-img>
          </v-col>
          
      <v-col
    cols="4">
    <v-img 
    height="350"
    src="https://i.pinimg.com/originals/02/06/17/02061718508618c2ca82625022702e97.jpg">
      <div >
          sky
      </div>
      <v-card-actions>
          <v-btn text>
              <a
              style="text-decoration: none; color: aliceblue"
              href="https://www.pinterest.com/pin/623889354643213311/"
                    target="_blank"
                    rel="noopener noreferrer"
                    >View</a>
          </v-btn>
      </v-card-actions>
      
    </v-img>
  </v-col>

  <v-col
    cols="4">
    <v-img 
    height="350"
    src="https://i.pinimg.com/originals/4a/74/5a/4a745a1e84a9e61e6ca2cf2a87a5c7ef.jpg">
      <div >
          flower
      </div>
      <v-card-actions>
          <v-btn text>
              <a
              style="text-decoration: none; color: aliceblue"
              href="https://www.pinterest.com/pin/595601119484838453/"
                    target="_blank"
                    rel="noopener noreferrer"
                    >View</a>
          </v-btn>
      </v-card-actions>
    </v-img>
  </v-col>

  <v-col
    cols="15">
    <v-img 
    height="200"
    src="http://interfacelift.com/wallpaper/previews/03687_manarola5terre_672x420.jpg">
      <div >
          City
      </div>
      <v-card-actions>
          <v-btn text>
              <a
              style="text-decoration: none; color: aliceblue"
              href="https://www.pinterest.com/pin/595601119484838453/"
                    target="_blank"
                    rel="noopener noreferrer"
                    >View</a>
          </v-btn>
      </v-card-actions>
    </v-img>
  </v-col>

        </v-row>
    </v-container>
    
    <div class="pa-10 text-center">
      ANIMATION
      </div>
  </v-col>

<v-col col="10 md=6"> 
<iframe width="600" height="340" 
src="https://www.youtube.com/embed/ZAxcN2xz0so" 
title="YouTube video player"
frameborder="0" 
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen>
</iframe>
</v-col>
      
  <v-lazy
        v-model="isActive"
        :options="{
          threshold: .5
        }"
        min-height="200"
        transition="fade-transition"
      >
       
      </v-lazy>
    </v-responsive>
  </v-responsive>
  
</template>

 
<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://images.indulgexpress.com/uploads/user/imagelibrary/2020/12/10/original/WhyDontWe.jpg?w=400&dpr=2.6',
         
          },
          {
            src: 'https://www.billboard.com/wp-content/uploads/media/Ariana-Grande-x-bb27-2018-feat-billboard-airgbghejr-1548.jpg',
          },
          {
            src: 'https://www.billboard.com/wp-content/uploads/2021/02/The-Weeknd-cr-Pari-Dukovic-CAA-billboard-1548-1614187803.jpg',
          },
          {
            src: 'https://thomasthailand.co/wp-content/uploads/2021/06/AW-Post-malone-02-scaled.jpg',
          },
        ],
      }
    },
  }
</script>