<script >
import TopInfoVue from './components/TopInfo.vue';
import HeaderAppVue from './components/HeaderApp.vue';
import JumboAppVue from './components/JumboApp.vue';
import ServicesAppVue from './components/ServicesApp.vue';
import CompanyAppVue from './components/CompanyApp.vue';
import ProjectsAppVue from './components/ProjectsApp.vue';
import ResultsAppVue from './components/ResultsApp.vue';

export default {
  components: {
    TopInfoVue,
    HeaderAppVue,
    JumboAppVue,
    ServicesAppVue,
    CompanyAppVue,
    ProjectsAppVue,
    ResultsAppVue,
  }
}
</script>

<template>

  <TopInfoVue />

  <div class="shared_bg">
    <HeaderAppVue />
    <JumboAppVue />
  </div>

  <ServicesAppVue />
  <CompanyAppVue />
  <ProjectsAppVue />
  <ResultsAppVue />
</template>

<style lang="scss">
@use "./styles/general.scss" as *;

.shares_bg {
  background-image: url("./assets/img/bg-jumbo.webp");
}
</style>
