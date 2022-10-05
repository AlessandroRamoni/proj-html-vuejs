<template>
  <div id="app">
    <NavComponent />
    <HeaderComponent />
    <MainComponent />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainComponent from "@/components/MainComponent.vue";

export default {
  name: "App",
  components: {
    NavComponent,
    HeaderComponent,
    MainComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
</style>
