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
    <v-row justify="center" no-gutters class="mb-10">
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
    <v-card tile color="primary" height="1000" flat class="mb-10">
      <v-card-title
        class="justify-center text-h2 font-weight-medium white--text"
      >
        Makers Projects
      </v-card-title>
      <v-divider class="mx-16 mb-10"></v-divider>
      <v-row class="justify-center" no-gutters>
        <v-col cols="4" align-self="center">
          <div class="d-flex justify-center">
            <v-img
              src="team_pic_1.png"
              class="rounded-xl"
              style="opacity: 0.5"
              height="200"
              max-width="300"
            >
            </v-img>
          </div>
        </v-col>
        <v-spacer></v-spacer>
        <v-col cols="3">
          <v-carousel hide-delimiters height="300">
            <v-carousel-item>
              <v-sheet height="100%" color="transparent">
                <v-row class="fill-height" align="center" justify="center">
                  <v-img
                    src="team_pic_1.png"
                    max-width="420"
                    height="270"
                    class="rounded-xl"
                  ></v-img>
                </v-row>
              </v-sheet>
            </v-carousel-item>
          </v-carousel>
          <v-row justify="center" class="pa-5">
            <v-col class="text-center">
              <div class="text-h3 font-weight-light mb-10">LGS</div>
              <div class="white--text text-subtitle-1 text-justify">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                aliquip ex ea commodo consequat.
              </div>
              <v-divider class="my-5"></v-divider>
              <v-btn rounded color="secondary" elevation="10">
                Learn More
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
        <v-spacer></v-spacer>
        <v-col cols="4" align-self="center">
          <div class="d-flex justify-center">
            <v-img
              src="team_pic_1.png"
              class="rounded-xl"
              style="opacity: 0.5"
              height="200"
              max-width="300"
            >
            </v-img>
          </div>
        </v-col>
      </v-row>
    </v-card>
    <div class="text-center text-h2 font-weight-medium primary--text mb-10">
      Makers experiences
    </div>
    <v-divider class="mx-16 mb-16"></v-divider>
    <v-row justify="center" no-gutters class="mb-10">
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
      <v-col cols="3" class="mx-10 py-10">
        <v-card height="400" flat>
          <v-avatar size="128" color="secondary" class="mb-10">
            <img src="https://cdn.vuetifyjs.com/images/john.jpg" />
          </v-avatar>
          <v-spacer></v-spacer>
          <div class="text-h3 mb-5">Robotics</div>
          <div class="text-subtitle-1 font-weight-light text-justify">
            Robotics is an interdisciplinary field that integrates computer
            science and engineering. Robotics involves design, construction,
            operation, and use of robots. The goal of robotics is to design
            machines that can help and assist humans
          </div>
        </v-card>
      </v-col>
    </v-row>
    <div class="text-center text-h2 font-weight-medium primary--text mb-10">
      Feedbacks
    </div>
    <v-divider class="mx-16 mb-3"></v-divider>
    <v-carousel
      height="900px"
      progress
      cycle
      hide-delimiter-background
      hide-delimiters
    >
      <v-carousel-item
        reverse-transition="fade-transition"
        transition="fade-transition"
      >
        <v-sheet color="white" height="100%">
          <v-row class="fill-height" align="center" justify="center">
            <v-col cols="5">
              <v-avatar size="100" style="opacity: 0.6">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQG-1fS10PCYAQ/profile-displayphoto-shrink_800_800/0/1631740790908?e=1639008000&v=beta&t=gqpxMH1v4Wurv-zcWLMQXo2sKGQLY4P3f3liFtO6pBI"
                >
                </v-img>
              </v-avatar>
              <v-avatar size="400" class="mx-5">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQGoTdFxO5tO_g/profile-displayphoto-shrink_800_800/0/1625912414878?e=1639008000&v=beta&t=acpzowt7Y4cvidd-o3o05ED_vSo8xGZXuNscnLtmVOE"
                >
                </v-img>
              </v-avatar>
              <v-avatar size="100" style="opacity: 0.6">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQFdPLq3P3vzdQ/profile-displayphoto-shrink_800_800/0/1630102880162?e=1639008000&v=beta&t=s2NLvAoufhQiR7VKIKOsNfMAb9FblQebR1qLjYFcWlI"
                >
                </v-img>
              </v-avatar>
            </v-col>
            <v-col cols="5">
              <div class="text-h1 mb-3 font-weight-bold">Raad Kloob</div>
              <div class="text-h4 mb-16">Graphic Designer</div>
              <div class="text-subtitle-1 font-weight-light text-justify">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor
                in hendrerit in vulputate velit esse molestie consequat, vel
                illum dolore eu feugiat nulla facilisis at vero eros et accumsan
                et iusto odio dignissim qui blandit praesent luptatum zzril
                delenit augue duis dolore te feugait nulla facilisi.
              </div>
            </v-col>
          </v-row>
        </v-sheet>
      </v-carousel-item>
      <v-carousel-item
        reverse-transition="fade-transition"
        transition="fade-transition"
      >
        <v-sheet color="white" height="100%">
          <v-row class="fill-height" align="center" justify="center">
            <v-col cols="5">
              <v-avatar size="100" style="opacity: 0.6">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQGoTdFxO5tO_g/profile-displayphoto-shrink_800_800/0/1625912414878?e=1639008000&v=beta&t=acpzowt7Y4cvidd-o3o05ED_vSo8xGZXuNscnLtmVOE"
                >
                </v-img>
              </v-avatar>
              <v-avatar size="400" class="mx-5">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQFdPLq3P3vzdQ/profile-displayphoto-shrink_800_800/0/1630102880162?e=1639008000&v=beta&t=s2NLvAoufhQiR7VKIKOsNfMAb9FblQebR1qLjYFcWlI"
                >
                </v-img>
              </v-avatar>
              <v-avatar size="100" style="opacity: 0.6">
                <v-img
                  src="https://media-exp1.licdn.com/dms/image/C4D03AQG-1fS10PCYAQ/profile-displayphoto-shrink_800_800/0/1631740790908?e=1639008000&v=beta&t=gqpxMH1v4Wurv-zcWLMQXo2sKGQLY4P3f3liFtO6pBI"
                >
                </v-img>
              </v-avatar>
            </v-col>
            <v-col cols="5">
              <div class="text-h1 mb-3 font-weight-bold">Ali Albustami</div>
              <div class="text-h4 mb-16">Team Leader</div>
              <div class="text-subtitle-1 font-weight-light text-justify">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed
                diam nonummy nibh euismod tincidunt ut laoreet dolore magna
                aliquam erat volutpat. Ut wisi enim ad minim veniam, quis
                nostrud exerci tation ullamcorper suscipit lobortis nisl ut
                aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor
                in hendrerit in vulputate velit esse molestie consequat, vel
                illum dolore eu feugiat nulla facilisis at vero eros et accumsan
                et iusto odio dignissim qui blandit praesent luptatum zzril
                delenit augue duis dolore te feugait nulla facilisi.
              </div>
            </v-col>
          </v-row>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
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
