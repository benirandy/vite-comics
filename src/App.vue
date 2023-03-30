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

  <main> Contents go here</main>

  <TheFooter></TheFooter>
</template>

<style lang="scss">
@use "./styles/general.scss";
</style>