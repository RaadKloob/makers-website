<template>
  <v-app>
    <v-navigation-drawer color="primary" v-model="drawer" app>
    </v-navigation-drawer>
    <v-app-bar app color="secondary" dark src="app_bar.png">
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      <img src="word_logo.png" alt="makers-logo" height="60" class="mx-8" />
      <v-spacer></v-spacer>
      <v-btn text tile x-large> About Us </v-btn>
      <v-divider vertical inset></v-divider>
      <v-btn text tile x-large style="text-transform: none"> Portfolio </v-btn>
      <v-divider vertical inset></v-divider>
      <v-btn text tile x-large style="text-transform: none"> Courses </v-btn>
      <v-divider vertical inset></v-divider>

      <v-btn text tile x-large style="text-transform: none"> Gallery </v-btn>
      <v-divider vertical inset></v-divider>

      <v-btn text tile x-large style="text-transform: none"> Contact Us </v-btn>
    </v-app-bar>
    <v-main>
      <router-view></router-view>
    </v-main>
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
