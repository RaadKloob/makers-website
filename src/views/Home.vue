<template>
  <div dark>
    <v-row>
      <v-col cols="12">
        <v-card outlined flat tile height="700">
          <v-carousel cycle height="700" delimiter-icon="mdi-minus">
            <v-carousel-item src="team_pic_1.png" class="blur">
              <v-card class="ma-10 px-16 transparent" flat>
                <v-card-title
                  class="text-h2 font-weight-bold white--text"
                  style="line-height: normal"
                >
                  Makers <br />
                  Achievements
                </v-card-title>
                <v-row>
                  <v-col cols="8">
                    <v-card-subtitle
                      class="white--text text-subtitle-1 text-justify"
                    >
                      Lorem ipsum dolor sit amet, consectetuer adipiscing elit,
                      sed diam nonummy nibh euismod tincidunt ut laoreet dolore
                      magna aliquam erat volutpat. Ut wisi enim ad minim veniam,
                      quis nostrud exerci tation ullamcorper suscipit lobortis
                      nisl ut aliquip ex ea commodo consequat. Duis autem vel
                      eum iriure dolor in hendrerit in vulputate velit esse
                      molestie consequat, vel illum dolore eu feugiat nulla
                      facilisis at vero eros et accumsan et iusto odio dignissim
                      qui blandit praesent luptatum zzril delenit augue duis
                      dolore te feugait nulla facilisi. Lorem ipsum dolor sit
                      amet, cons ectetuer adipiscing elit, sed diam nonummy nibh
                      euismod tincidunt ut laoreet dolore magna aliquam erat
                      volutpat. Ut wisi enim ad minim veniam, quis nostrud
                      exerci tation ullamcorper suscipit lobortis nisl ut
                      aliquip ex ea commodo consequat. Lorem ipsum dolor sit
                      amet, consectetuer adipiscing elit, sed diam nonummy nibh.
                    </v-card-subtitle>
                  </v-col>
                  <v-col cols="4"> </v-col>
                </v-row>
                <v-divider class="my-13" hidden></v-divider>
                <v-btn rounded x-large color="primary" elevation="10">
                  Learn More
                </v-btn>
              </v-card>
            </v-carousel-item>
            <v-carousel-item src="team_pic_1.png" class="blur">
              <v-card class="ma-10 px-16 transparent" flat>
                <v-card-title
                  class="text-h2 font-weight-bold white--text"
                  style="line-height: normal"
                >
                  Makers <br />
                  Achievements
                </v-card-title>
                <v-row>
                  <v-col cols="8">
                    <v-card-subtitle
                      class="white--text text-subtitle-1 text-justify"
                    >
                      Lorem ipsum dolor sit amet, consectetuer adipiscing elit,
                      sed diam nonummy nibh euismod tincidunt ut laoreet dolore
                      magna aliquam erat volutpat. Ut wisi enim ad minim veniam,
                      quis nostrud exerci tation ullamcorper suscipit lobortis
                      nisl ut aliquip ex ea commodo consequat. Duis autem vel
                      eum iriure dolor in hendrerit in vulputate velit esse
                      molestie consequat, vel illum dolore eu feugiat nulla
                      facilisis at vero eros et accumsan et iusto odio dignissim
                      qui blandit praesent luptatum zzril delenit augue duis
                      dolore te feugait nulla facilisi. Lorem ipsum dolor sit
                      amet, cons ectetuer adipiscing elit, sed diam nonummy nibh
                      euismod tincidunt ut laoreet dolore magna aliquam erat
                      volutpat. Ut wisi enim ad minim veniam, quis nostrud
                      exerci tation ullamcorper suscipit lobortis nisl ut
                      aliquip ex ea commodo consequat. Lorem ipsum dolor sit
                      amet, consectetuer adipiscing elit, sed diam nonummy nibh.
                    </v-card-subtitle>
                  </v-col>
                  <v-col cols="4"> </v-col>
                </v-row>
                <v-divider class="my-13" hidden></v-divider>
                <v-btn rounded x-large color="primary" elevation="10">
                  Learn More
                </v-btn>
              </v-card>
            </v-carousel-item>
          </v-carousel>
          <!-- <video-background src="intro.mp4" id="backgroundVideo">
          </video-background> -->
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
// import VideoBackground from "vue-responsive-video-background-player";

export default {
  name: "Home",
  components: {
    // VideoBackground,
  },
};
</script>
<style >
#backgroundVideo {
  max-height: 500px;
  height: 100vh;
}
.blur .v-image__image {
  filter: blur(4px);
  -webkit-filter: blur(4px);
}
</style>
