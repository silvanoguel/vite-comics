<script>

import AppHeader from "./components/AppHeader.vue";
import AppBanner from "./components/AppBanner.vue";
import AppMain from "./components/AppMain.vue";
import AppFeatures from "./components/AppFeatures.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppBanner,
    AppMain,
    AppFeatures,
    AppFooter,
  },
  data() {
    return {
      banner: [
        {
          image: "jumbotron.jpg",
          title: "CURRENT SERIES",
        }
      ]
    }
  }
}

</script>

<template>
  <AppHeader />
  <AppBanner v-for="(banner, index) in banner" :key="index" :image="banner.image" :title="banner.title"/>
  <AppMain />
  <AppFeatures />
  <AppFooter />

</template>

<style lang="scss">
@use "./style/general.scss" as *;
</style>
