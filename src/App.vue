<template>
  <v-app>
    <v-navigation-drawer color="primary" v-model="drawer" app>
    </v-navigation-drawer>
    <v-app-bar app color="secondary" dark src="app_bar.png" tile flat>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      <router-link to="/">
        <img src="word_logo.png" alt="makers-logo" height="60" class="mx-8" />
      </router-link>
      <v-spacer></v-spacer>
      <v-btn text tile x-large to="/about"> About Us </v-btn>
      <v-divider vertical inset></v-divider>
      <v-btn text tile x-large> Portfolio </v-btn>
      <v-divider vertical inset></v-divider>
      <v-btn text tile x-large> Courses </v-btn>
      <v-divider vertical inset></v-divider>

      <v-btn text tile x-large> Gallery </v-btn>
      <v-divider vertical inset></v-divider>

      <v-btn text tile x-large style="text-transform: none" to="/contact">
        Contact Us
      </v-btn>
    </v-app-bar>
    <v-main>
      <router-view></router-view>
    </v-main>
    <v-footer padless color="secondary" height="350" class="pt-16">
      <v-row justify="start" class="fill-height">
        <v-col cols="4">
          <div class="d-flex justify-center mb-10">
            <v-img src="word_logo.png" max-height="80" max-width="250"></v-img>
          </div>
          <div class="d-flex justify-center">
            <div
              class="primary mx-2"
              style="
                height: 30px;
                width: 30px;
                border-radius: 50%;
                display: inline-block;
              "
            ></div>
            <div
              class="primary mx-3"
              style="
                height: 30px;
                width: 30px;
                border-radius: 50%;
                opacity: 0.7;
                display: inline-block;
              "
            ></div>
            <div
              class="primary mx-2"
              style="
                height: 30px;
                width: 30px;
                border-radius: 50%;
                opacity: 0.5;
                display: inline-block;
              "
            ></div>
          </div>
        </v-col>
        <v-col cols="2">
          <div class="text-h4 white--text mb-6">Sample Menu</div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
        </v-col>
        <v-col cols="2">
          <div class="text-h4 white--text mb-6">Sample Menu</div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            Sample Menu
          </div>
        </v-col>
        <v-col cols="3">
          <div class="text-h4 white--text mb-6">Our Company</div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            <v-icon left color="primary"> mdi-home </v-icon>tincidunt ut laoreet
            dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam,
            quis nostrud exerci tation
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            <v-icon left color="primary"> mdi-email </v-icon>test@gmail.com
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            <v-icon left color="primary"> mdi-phone </v-icon>+962 079 555 1887
          </div>
          <div class="subtitle-1 white--text mb-3 font-weight-light">
            All the Love ! ❤️
          </div>
        </v-col>
      </v-row>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    drawer: false,
  }),
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans");
$body-font-family: "Open Sans";
$heading-font-family: "Montserrat";
$title-font: "Montserrat";
.v-application {
  [class*="text-"] {
    font-family: $title-font, sans-serif !important;
  }
  font-family: $body-font-family, sans-serif !important;
  .text-align-center {
    text-align: center !important;
  }
  .text-align-right {
    text-align: right !important;
  }
}
.v-btn {
  text-transform: none !important;
}
</style>
