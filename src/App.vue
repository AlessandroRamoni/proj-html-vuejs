<template>
  <div id="app">
    <NavComponent />
    <HeaderComponent />
    <MainComponent />
    <StatisticsComponent />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainComponent from "@/components/MainComponent.vue";
import StatisticsComponent from "@/components/StatisticsComponent.vue";

export default {
  name: "App",
  components: {
    NavComponent,
    HeaderComponent,
    MainComponent,
    StatisticsComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
</style>
