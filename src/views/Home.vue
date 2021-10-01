<template>
  <div class="ma-0 pa-0">
    <v-card flat tile height="700" class="mb-10">
      <v-carousel
        cycle
        height="700"
        delimiter-icon="mdi-minus"
        show-arrows-on-hover
      >
        <v-carousel-item src="team_pic_1.png" class="blur">
          <v-card class="ma-10 px-16 transparent" flat>
            <v-card-title class="text-h2 font-weight-bold white--text">
              Makers <br />
              Achievements
            </v-card-title>
            <v-row>
              <v-col cols="8">
                <v-card-subtitle
                  class="white--text text-subtitle-1 text-justify"
                >
                  Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                  diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                  aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                  nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                  aliquip ex ea commodo consequat. Duis autem vel eum iriure
                  dolor in hendrerit in vulputate velit esse molestie consequat,
                  vel illum dolore eu feugiat nulla facilisis at vero eros et
                  accumsan et iusto odio dignissim qui blandit praesent luptatum
                  zzril delenit augue duis dolore te feugait nulla facilisi.
                  Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed
                  diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                  aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                  nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                  aliquip ex ea commodo consequat. Lorem ipsum dolor sit amet,
                  consectetuer adipiscing elit, sed diam nonummy nibh.
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
            <v-card-title class="text-h2 font-weight-bold white--text">
              Makers <br />
              Achievements
            </v-card-title>
            <v-row>
              <v-col cols="8">
                <v-card-subtitle
                  class="white--text text-subtitle-1 text-justify"
                >
                  Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                  diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                  aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                  nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                  aliquip ex ea commodo consequat. Duis autem vel eum iriure
                  dolor in hendrerit in vulputate velit esse molestie consequat,
                  vel illum dolore eu feugiat nulla facilisis at vero eros et
                  accumsan et iusto odio dignissim qui blandit praesent luptatum
                  zzril delenit augue duis dolore te feugait nulla facilisi.
                  Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed
                  diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                  aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                  nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                  aliquip ex ea commodo consequat. Lorem ipsum dolor sit amet,
                  consectetuer adipiscing elit, sed diam nonummy nibh.
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
    <div class="text-center text-h2 font-weight-medium primary--text mb-5">
      Makers Services
    </div>
    <v-divider class="mx-16 mb-10"></v-divider>
    <v-row justify="center" dense class="mb-10">
      <v-col cols="3" class="mx-7">
        <v-hover v-slot="{ hover }">
          <v-card
            outlined
            height="400"
            class="text-center secondary d-flex flex-column"
            :elevation="hover ? 24 : 0"
          >
            <v-card-title
              class="text-h3 justify-center font-weight-light white--text"
            >
              Software <br />
              Solutions
            </v-card-title>
            <v-spacer></v-spacer>
            <v-img
              src="software_solutions.png"
              alt="software_solutions"
              contain
              height="170"
            ></v-img>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="3" class="mx-7">
        <v-hover v-slot="{ hover }">
          <v-card
            outlined
            height="400"
            class="text-center secondary d-flex flex-column"
            :elevation="hover ? 24 : 0"
          >
            <v-card-title
              class="text-h3 justify-center font-weight-light white--text"
            >
              Hardware <br />
              Solutions
            </v-card-title>
            <v-spacer></v-spacer>
            <v-img
              src="hardware_solutions.png"
              alt="hardware_solutions"
              contain
              height="170"
            ></v-img>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="3" class="mx-7">
        <v-hover v-slot="{ hover }">
          <v-card
            outlined
            height="400"
            class="text-center secondary d-flex flex-column"
            :elevation="hover ? 24 : 0"
          >
            <v-card-title
              class="text-h3 justify-center font-weight-light white--text"
            >
              IOT <br />
              Solutions
            </v-card-title>
            <v-spacer></v-spacer>
            <v-img
              src="iot_solutions.png"
              alt="iot_solutions"
              contain
              height="170"
            ></v-img>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
    <v-card tile color="primary" height="700">
      <v-card-title
        class="justify-center text-h2 font-weight-medium white--text"
      >
        Makers Projects
      </v-card-title>
      <v-divider class="mx-16 mb-10"></v-divider>
      <v-card-actions>
        <v-row class="justify-center">
          <v-col cols="4">
            <div class="d-flex justify-center">
              <img
                src="team_pic_1.png"
                class="rounded-xl"
                style="opacity: 0.5; object-fit: cover"
                height="300"
                width="400"
              />
            </div>
          </v-col>
          <v-col cols="3">
            <v-carousel hide-delimiters height="300">
              <v-carousel-item>
                <div class="d-flex justify-center">
                  <img
                    src="team_pic_1.png"
                    class="rounded-xl"
                    height="300"
                    width="400"
                  />
                </div>
              </v-carousel-item>
              <v-carousel-item>
                <div class="d-flex justify-center">
                  <img
                    src="team_pic_1.png"
                    class="rounded-xl"
                    height="300"
                    width="400"
                  />
                </div>
              </v-carousel-item>
            </v-carousel>
          </v-col>
          <v-col cols="4">
            <div class="d-flex justify-center">
              <img
                src="team_pic_1.png"
                class="rounded-xl"
                style="opacity: 0.5"
                height="300"
                width="400"
              />
            </div>
          </v-col>
        </v-row>
      </v-card-actions>
    </v-card>
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
<style lang="scss">
#backgroundVideo {
  max-height: 500px;
  height: 100vh;
}
.blur .v-image__image {
  filter: blur(4px);
  -webkit-filter: blur(4px);
}
.v-card__title {
  line-height: normal !important;
}
</style>
