<template>
  <div>
    <v-card tile flat class="pa-md-10 pa-5 text-center" color="surface">
      <h2 class="text-md-h6 font-weight-bold">Smooth Flight Support</h2>
      <div class="text-center">
        <v-btn v-for="(b,i) in sm" :key="`socialMedia-${i}`" color="surface" class="mr-2" fab depressed>
          <v-icon>{{ b.icon }}</v-icon>
        </v-btn>
      </div>
    </v-card>
  </div>
</template>

<script>
export default {
  name: 'FooterPage',
        data () {
          return {
      sm: [
        {
          icon: "mdi-facebook",
          link: "#",
        },
        {
          icon: "mdi-twitter",
          link: "#",
        },
        {
          icon: "mdi-instagram",
          link: "#",
        },
        {
          icon: "mdi-youtube",
          link: "#",
        },
      ],


    };
  },
};
</script>

<style>

</style>
