<template>
  <div id="app">
    <NavComponent />
    <HeaderComponent />
    <MainComponent />
    <StatisticsComponent />
    <OurClassesComponent />
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainComponent from "@/components/MainComponent.vue";
import StatisticsComponent from "@/components/StatisticsComponent.vue";
import OurClassesComponent from "@/components/OurClassesComponent.vue";

export default {
  name: "App",
  components: {
    NavComponent,
    HeaderComponent,
    MainComponent,
    StatisticsComponent,
    OurClassesComponent,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/standard.scss";
@import url("https://fonts.googleapis.com/css2?family=Gemunu+Libre&family=Open+Sans&display=swap");
#app {
  font-family: "Open Sans", sans-serif;
}
</style>
