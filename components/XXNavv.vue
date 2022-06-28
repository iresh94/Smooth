<template>
  <div>
    <v-card
   class="mx-auto"
   rounded="0" max-width="1450" height="51" outlined elevation="0"
   color="#20425D" app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
    }">

      <v-app-bar
      dense
      justify="center"
      align="center"
      elevation="0"
      height="50"
      color="#20425D"
      dark
      fade-img-on-scroll
      scroll-target="#scrolling-techniques-4"
      >

        <v-menu bottom left>
        </v-menu>

        <v-tabs align-with-title>

            <v-tab>
            Home
            </v-tab>

              <v-tab>
               Services
              </v-tab>

            <v-tab>
            About Us
            </v-tab>

            <v-tab>
            News
            </v-tab>

            <v-tab>
            Careers
            </v-tab>

            <v-tab>
            Contact Us
            </v-tab>
        </v-tabs>

      </v-app-bar>
    </v-card>
  </div>
</template>



<script>
export default {
  name: "NavvPage",


}
</script>
