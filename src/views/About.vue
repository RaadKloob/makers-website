<template>
  <div class="pb-16">
    <v-row no-gutters class="pa-8">
      <v-col cols="2">
        <v-img
          src="logo.png"
          class="ml-n8"
          aspect-ratio="0.5"
          width="300"
          position="100% 50%"
        ></v-img>
      </v-col>
      <v-col cols="10" class="pt-16">
        <v-row justify="center">
          <v-col cols="10">
            <div class="text-h2 font-weight-bold primary--text mb-3">
              Makers Team
            </div>
            <div class="text-h5 secondary--text font-weight-light mb-8">
              Lorem ipsum dolor
            </div>
            <div class="body-1 secondary--text text-justify">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam
              nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam
              erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci
              tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo
              consequat. Duis autem vel eum iriure dolor in hendrerit in
              vulputate velit esse molestie consequat, vel illum dolore eu
              feugiat nulla facilisis at vero eros et accumsan et iusto odio
              dignissim qui blandit praesent luptatum zzril delenit augue duis
              dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, cons
              ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt
              ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad
              minim veniam, quis nostrud exerci tation ullamcorper suscipit
              lobortis
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <v-divider class="mb-10"></v-divider>
    <div class="text-h3 font-weight-bold primary--text mb-10 text-center">
      Makers Members
    </div>
    <v-row justify="center">
      <v-col cols="3">
        <v-carousel
          height="100%"
          hide-delimiter-background
          hide-delimiters
          v-model="slider"
        >
          <v-carousel-item v-for="member in members" :key="member.id">
            <div class="d-flex justify-center">
              <v-avatar size="75%">
                <v-img :src="member.photo"> </v-img>
              </v-avatar>
            </div>
          </v-carousel-item>
        </v-carousel>
      </v-col>
    </v-row>
    <v-row justify="space-around">
      <v-col cols="3">
        <div class="d-flex justify-center">
          <div
            class="
              secondary
              lighten-4
              py-3
              mb-3
              font-weight-bold
              text-h4
              white--text
              text-center
              rounded
            "
            style="width: 80%"
          >
            {{ currentMember[0].name }}
          </div>
        </div>
        <div class="d-flex justify-center">
          <div class="secondary--text font-weight-regular text-h6 text-center">
            {{ currentMember[0].jobTitle }}
          </div>
        </div>
        <div class="d-flex justify-center">
          <v-btn
            icon
            x-large
            :href="currentMember[0].facebook"
            target="_blank"
            class="ma-2"
          >
            <v-icon x-large color="#3b5998">mdi-facebook</v-icon>
          </v-btn>
          <v-btn
            icon
            x-large
            :href="currentMember[0].linkedin"
            target="_blank"
            class="ma-2"
          >
            <v-icon x-large color="#0e76a8">mdi-linkedin</v-icon>
          </v-btn>
          <v-btn
            icon
            x-large
            :href="currentMember[0].github"
            target="_blank"
            class="ma-2"
          >
            <v-icon x-large color="#333">mdi-github</v-icon>
          </v-btn>
        </div>
      </v-col>
    </v-row>
    <v-row justify="center">
      <v-col cols="6">
        <div class="body-1 font-weight-regular secondary--text text-justify">
          {{ currentMember[0].paragraph }}
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "About",
  components: {},

  data() {
    return {
      slider: 0,
      currentMember: {},
      members: [
        {
          id: 1,
          name: "Raad Kloob",
          photo:
            "https://media-exp1.licdn.com/dms/image/C4D03AQFjHS8is2XjIA/profile-displayphoto-shrink_800_800/0/1633443731250?e=1640217600&v=beta&t=QSBdeUh2M9BmmYcBUyUXlHdUEkPHeLkTrs0yEpHQ4S4",
          paragraph: `The endless capabilities of technology never failed to amaze me; and
          through the merging of the human brain and the power of an artificial
          brain, the limits of what is possible are stretched even further. This
          sparked my interest in technology, which consequently pushed me to
          teach myself technical skills at a young age, such as programming and
          embedded systems, eventually leading me to my latest project, “ADIRIS:
          Alzheimer's Disease Screening through the Iris”, which has won many
          competitions on an international level. As well as working on many
          projects such as“Smart Seniors Care” project which is a wearable that
          detects falls and monitors heart pulse for elderly. With this project,
          I was a finalist at Intel ISEF 2017 (International Science and
          Engineering Fair). Moreover, I spent my weekends working with my ROV
          team to achieve our goal of competing on an international level,
          eventually winning the Guts & Glory award in 2017 MATE ROV
          competition. Through these projects, I acquired technical skills such
          as making circuitry, 3D printing, troubleshooting, and using lab
          equipment to assemble projects. The projects that I worked on, made me
          admire this field even more. After years of learning, researching, and
          competing I finally had my first step towards achieving my dream of
          improving the world around me using technology. After working with my
          partner for months, and researching Alzheimer’s with many doctors, we
          designed an app that diagnoses Alzheimer’s through the iris using AI.
          This project eventually went on to win the Grand Gold Award in Genius
          Olympiad 2019, being a Finalist at Intel ISEF/2019. These competitions
          developed my understanding of this field, and the experiences I had
          from them shaped me into who I am today.`,
          jobTitle: "IT Developer",
          linkedin: "https://www.linkedin.com/in/raadkloob/",
          facebook: "https://www.facebook.com/raadkloob",
          github: "https://github.com/RaadKloob",
        },
        {
          id: 2,
          name: "Ali Bustami",
          photo:
            "https://media-exp1.licdn.com/dms/image/C4D03AQFdPLq3P3vzdQ/profile-displayphoto-shrink_800_800/0/1630102880162?e=1640217600&v=beta&t=5MrSfb3d4qkPrg2hb0DXFOP-5i-5vaFFNQx7DAxTVzI",
          paragraph: `The endless capabilities of technology never failed to amaze me; and
          through the merging of the human brain and the power of an artificial
          brain, the limits of what is possible are stretched even further. This
          sparked my interest in technology, which consequently pushed me to
          teach myself technical skills at a young age, such as programming and
          embedded systems, eventually leading me to my latest project, “ADIRIS:
          Alzheimer's Disease Screening through the Iris”, which has won many
          competitions on an international level. As well as working on many
          projects such as“Smart Seniors Care” project which is a wearable that
          detects falls and monitors heart pulse for elderly. With this project,
          .`,
          jobTitle: "Team Leader",
          linkedin: "https://www.linkedin.com/in/ali-albustami-0797b4189",
          facebook: "https://www.facebook.com/raadkloob",
          github: "https://github.com/RaadKloob",
        },
      ],
    };
  },

  watch: {
    slider(val) {
      console.log(this.currentMember);
      this.currentMember = this.members.filter((member) => {
        return member.id - 1 == val;
      });
    },
  },
};
</script>

<style lang="scss">
</style>