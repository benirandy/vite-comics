<script>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  components: {
    TheHeader,
    TheFooter,
  },
  data() { },
  methods: {},
};
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <h1>Contents goes here</h1>
  </main>

  <TheFooter></TheFooter>
</template>

<style lang="scss">
@use "./styles/general.scss";

footer {
  background-image: url(/img/footer-bg.jpg);
}
</style>