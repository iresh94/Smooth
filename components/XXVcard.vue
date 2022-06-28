<template>
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
        <v-specer />
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
          left
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
            class="ma-5 mx-0 font-weight-black font-color-white rounded-0"

            color="blue"
            padding-left="100"
            height="40"
            width="210"
            align="center"
            justify="center"
              >
            Smooth Flight Support
            </v-btn>
          </v-card-actions>
        </v-col>

      </v-row>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "VcardPage",

}



</script>
