<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import ProductList from "./components/ProductList.vue";

export default {
  components: {
    TheHeader,
    TheFooter,
    ProductList
  },
  data() { },
  methods: {},
};
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <ProductList />
  </main>

  <TheFooter></TheFooter>
</template>

<style lang="scss">
@use "./styles/general.scss";

main {background-image: url(/img/jumbotron.jpg);
}

footer {
  background-image: url(/img/footer-bg.jpg);
}
</style>