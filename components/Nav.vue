<template>


<div>

  <div>

    <v-card
    class="mx-auto" rounded="0" max-width="1650" height="40" outlined="0" elevation="0" color="#20425D" app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
    }">

<v-card-title
    class="text-md-h5 font-weight-bold pointer"
       @click="$router.push('/')"
>


</v-card-title>


    <v-breadcrumbs
      :items="items"
      divider=""
    >
    </v-breadcrumbs>
    </v-card>
  </div>




              <!-- logo-contact-btn START -->
    <div>
    <v-card
    class="mx-auto"
    rounded="0"
    max-width="1450"
    height="105"
    outlined
    elevation="0"
    color="white" app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
    }">
      <!-- <v-list-item three-line>
        <v-list-item-content>
          <div class="text-overline mb-4">
            OVERLINE
          </div>
          <v-list-item-title class="text-h5 mb-1">
            Headline 5
          </v-list-item-title>
          <v-list-item-subtitle>Greyhound divisely hello coldly fonwderfully</v-list-item-subtitle>
        </v-list-item-content>

        <v-list-item-avatar tile size="80" color="grey"></v-list-item-avatar>
      </v-list-item> -->
      <v-row>

        <!-- <v-img
          max-height="80"
          max-width="150"
          src="/"></v-img> -->

        <v-col cols="12" sm="2">
          <v-img
          justify="center"
          align="center"
          height="108"
          width="130px"
          src="/blue.png"
          aspect-ratio="7.1"
          contain
          >
          </v-img>
        </v-col>

<v-col cols="12" sm="2">
<v-list-item
 class="ma-6 mx-0"
>
        <v-list-item-content>
          <v-list-item-subtitle
          >
          <v-icon
          dense
          left
          color="cyan"
          >
        mdi-phone-outline
        </v-icon>
          Call Us Anytime
          </v-list-item-subtitle>
          <v-list-item-title
          class="font-weight-black"
          >(+94) 314354400</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
</v-col>

<v-divider
      class="ma-12 mx-0"
      vertical
    ></v-divider>

<v-col cols="12" sm="2">
<v-list-item
 class="ma-6 mx-0"
>
        <v-list-item-content>
          <v-list-item-subtitle>
          <v-icon
          dense
          left
          color="cyan"
          >
        mdi-clock-outline
        </v-icon>
          Opening Time
          </v-list-item-subtitle>
          <v-list-item-title
          class="font-weight-black"
          >
          24 Hrs
          </v-list-item-title>
        </v-list-item-content>
      </v-list-item>
</v-col>

<v-divider
      class="ma-12 mx-0"
      vertical
    ></v-divider>

<v-col cols="12" sm="3">
<v-list-item
 class="ma-6 mx-0"
>
        <v-list-item-content>
          <v-list-item-subtitle>
          <v-icon
          dense
          left="100"
          color="cyan"
          >
        mdi-email-outline
        </v-icon>
          Email Us
          </v-list-item-subtitle>
          <v-list-item-title
          class="font-weight-black"
          >
          info@smoothflightsupport.lk
          </v-list-item-title>
        </v-list-item-content>
      </v-list-item>
</v-col>

        <v-col cols="12" sm="2">
          <v-card-actions

          >
            <v-btn

            class="ma-6 mx-0 font-weight-black font-color-white rounded-0"

            color="blue"
            padding-left="150"
            height="40"
            width="210"
            align="center"
            justify="center"
            href="https://landingrequest.smoothflightsupport.lk/"
              >
            Landing Permit Request
            </v-btn>
          </v-card-actions>
        </v-col>
      </v-row>
    </v-card>
  </div>

                    <!-- logo-contact-btn END -->


                    <!-- app bar START -->

<div>
    <v-card
    :clipped-left="clipped" fixed
   class="mx-auto"
   rounded="0"
   max-width="1450"
   height="51"
   outlined
   elevation="0"
   color="#20425D"
   app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
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

            <v-tab link to="/About">
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

        <v-btn icon href="https://www.facebook.com/SmoothflightCmb">
        <v-icon size="25">mdi-facebook</v-icon>
      </v-btn>
      <v-btn icon href="https://twitter.com/flight_smooth">
        <v-icon size="25">mdi-twitter</v-icon>
      </v-btn>
      <v-btn icon href="https://www.instagram.com/smoothflightsupport/">
        <v-icon size="25">mdi-instagram</v-icon>
      </v-btn>
      <v-btn icon href="https://www.linkedin.com/company/smooth-flight-support-pvt-ltd/?originalSubdomain=lk">
        <v-icon size="25">mdi-linkedin</v-icon>
      </v-btn>
      <v-divider vertical class="mx-md-5 mx-2" />
      <v-btn icon>
        <v-icon size="25">mdi-brightness-7</v-icon>
      </v-btn>

      </v-app-bar>
    </v-card>
  </div>

                    <!-- app bar END -->


                    <div>

                    </div>
  </div>


</template>

<script>
export default {
  name: 'NavPage',
    data() {
    return {

    };
  },

};





</script>

<style>

</style>
