<template>
  <v-carousel
  hide-delimiters height="400"
  cycle
   >
    <v-carousel-item v-for="(item, i) in items" :key="i" :src="item.src"></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  name: "CarouselPage",
  data() {
    return {
      items: [
        {
          src:  '/one.jpg',
        },
        {
          src: '/two.jpg',
        },
        {
          src: '/tree.png',
        },

      ],
    }
  },
}
</script>
