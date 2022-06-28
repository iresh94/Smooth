<template>
<div>
            <!-- Nav App Bar Start -->

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

            <!-- Nav App Bar END -->

  <div>
    <v-card
    class="mx-auto" rounded="0" max-width="1650" height="180" outlined="0" elevation="0" color="#f1f1f1" app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
    }">

<v-row>
<v-col cols="12" sm="8">
<v-list-item
 class="ma-9 mx-0"
>
        <v-list-item-content>
          <v-list-item-title
          class="font-weight-black text-md-h3"
          >
          ABOUT US
          </v-list-item-title>

           <v-list-item-subtitle
           class="text-md-h6"
          >
          Something about us from a little bit of different perspective
          </v-list-item-subtitle>
        </v-list-item-content>

      </v-list-item>
</v-col>
</v-row>
    </v-card>
  </div>


  <div>
  <v-card
    class="mx-auto" rounded="0" max-width="1650" height="1180" outlined="0" elevation="0" color="white" app :style="{padding :$vuetify.breakpoint.mdAndUp ? '0px 100px': ''
    }">
  <v-row>
<v-col cols="12" sm="6">
<br />
<br />
         <p class="text-justify text--disabled font-weight-medium ">
    We are a flight support services providing company in Sri Lanka. We specialize in supporting flight operators that fly into the Middle East, Europe, CIS, Africa, Asia, and the Pacific. <br /> <br />

Our team assists aircraft operators in obtaining relevant permissions, providing regional flight planning advice, and making the necessary arrangements for aircraft handling services, hotel reservations, and transportation arrangements to make your experience effortless. <br /><br />

Smooth Flight Support Company has a team of experienced professionals dedicated to ensuring you receive a first-class service for all your flight preparations and requirements. Smooth Flight Support Company team is available 24 hours a day, every day of the year to meet customers’ trip requirements. Smooth Flight Support Company arrangements and give you more time to on your crew, your VIP passengers, and your flight. Whatever your needs Smooth Flight Support Company is here to assist you. <br/><br/>

Smooth Flight Support's primary objective is the quality of service and the wellbeing of all our customers. We provide excellent services and guarantee a hassle-free and enjoyable travel experience.
  </p>
<br/>
  <p class="font-weight-black text-md-h5">
  Our Vision
  </p>

  <br />

  <p class="text-justify text--disabled font-weight-medium ">
  To be the leader in the ground flight support sector while providing our clients exceptional service in every aspect comply with international standards with the cutting edge technology in Sri Lanka.
  </p>
</v-col>



<v-col cols="12" sm="6">
<br/><br/>
 <v-img
          justify="center"
          align="center"
          max-height="380"
        max-width="1200"
          src="/about.jpg"
          aspect-ratio="0.1"
          contain
          >
          </v-img>

          <br/><br/><br/><br/><br/>
  <p class="font-weight-black text-md-h5">
  Our Mission
  </p>

  <br />

  <p class="text-justify text--disabled font-weight-medium ">
  To provide our clients the best solutions in the ground handling services with reliable, safe, fast, and effective operation ensuring the best quality service.
  </p>
</v-col>

  </v-row>
  </v-card>
  </div>






</div>
</template>




<script>
export default {
  name: "BtnPage",
  return() {

  }
}
</script>
