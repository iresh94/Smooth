<template>
  <div>
    <Nav />
    <!-- <Vcard /> -->
    <!-- <Navv /> -->
    <Carousel />
    <Footer />
    <About />





    <!-- <Nav1 /> -->

    <!-- <HomeCarousel :sale_items="sale_items" /> -->
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      products: null,
      sale_items : null,
    };
  },
  async created() {
    this.sale_items = await this.$content("products")
      .where({ onSale: true })
      .fetch();
    this.products = await this.$content("products").fetch();
  },
};

</script>

<style>

</style>
