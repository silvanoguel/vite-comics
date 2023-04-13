<script>

import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue";
// import AppFeatures from "./components/AppFeatures.vue";
// import AppFooter from "./components/AppFooter.vue";


export default {
  components: {
    AppHeader,
    AppMain,
    // AppFeatures,
    // AppFooter
  }
}

</script>

<template>
  <AppHeader />
  <AppMain />

</template>

<style lang="scss">
@use "./style/general.scss" as *;
</style>
