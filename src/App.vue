<script >
import TopInfoVue from './components/TopInfo.vue';
import HeaderAppVue from './components/HeaderApp.vue';
import JumboAppVue from './components/JumboApp.vue';
import ServicesAppVue from './components/ServicesApp.vue';

export default {
  components: {
    TopInfoVue,
    HeaderAppVue,
    JumboAppVue,
    ServicesAppVue,

  }
}
</script>

<template>

  <TopInfoVue />

  <div class="ciao">
    <HeaderAppVue />
    <JumboAppVue />
  </div>

  <ServicesAppVue />


</template>

<style lang="scss">
@use "./styles/general.scss" as *;

.ciao {
  background-image: url("./assets/img/bg-jumbo.webp");
}
</style>
