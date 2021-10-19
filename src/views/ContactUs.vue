<template>
  <div class="pa-8 pb-16">
    <v-row>
      <v-col cols="5">
        <div class="text-h2 primary--text font-weight-bold mb-2">
          Contact Us
        </div>
        <v-divider class="mb-5"></v-divider>
        <div class="font-weight-bold text-justify mb-16 secondary--text">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam
          nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat
          volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation
          ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo
        </div>
        <v-text-field label="Name"></v-text-field>
        <v-text-field label="Email"></v-text-field>
        <v-textarea label="Message" rows="6" class="mb-5" no-resize>
        </v-textarea>
        <div class="d-flex justify-start">
          <v-btn
            depressed
            tile
            large
            color="primary"
            class="font-weight-bold"
            width="30%"
          >
            SEND
          </v-btn>
        </div>
      </v-col>
      <v-col cols="7">
        <div class="d-flex justify-center">
          <v-img
            max-width="60%"
            class="mb-16"
            src="http://unblast.com/wp-content/uploads/2020/09/Contact-Us-Vector-Illustration-1.jpg"
          >
          </v-img>
        </div>
        <v-row justify="center" align="center" class="mb-5">
          <v-col cols="4">
            <div class="text-h6 font-weight-bold secondary--text mr-16">
              <v-icon size="60" color="primary" class="mr-1"
                >mdi-facebook</v-icon
              >Makers.Team.Jo
            </div>
          </v-col>
          <v-col cols="4">
            <div class="text-h6 font-weight-bold secondary--text">
              <v-icon size="60" color="primary" class="mr-1">mdi-twitter</v-icon
              >MakersJo
            </div>
          </v-col>
        </v-row>
               <v-row justify="center" align="center" class="mb-5">
          <v-col cols="4">
            <div class="text-h6 font-weight-bold secondary--text mr-16">
              <v-icon size="60" color="primary" class="mr-1"
                >mdi-linkedin</v-icon
              >Makers Team
            </div>
          </v-col>
          <v-col cols="4">
            <div class="text-h6 font-weight-bold secondary--text">
              <v-icon size="60" color="primary" class="mr-1">mdi-instagram</v-icon
              >makers.jo
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
</style>