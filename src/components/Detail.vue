<template>
  <v-container text>
    <h1>รายละเอียดสินค้า</h1>
    <h2>{{ productid }}. {{ description }}</h2>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      productid: this.$route.params.id,
      description: this.$route.params.description,
    };
  },
};
</script>

<style></style>
