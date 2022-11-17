<script >
import TopInfoVue from './components/TopInfo.vue';
import HeaderAppVue from './components/HeaderApp.vue';
import JumboAppVue from './components/JumboApp.vue';

export default {
  components: {
    TopInfoVue,
    HeaderAppVue,
    JumboAppVue,

  }
}
</script>

<template>
  <TopInfoVue />
  <div class="ciao">
    <HeaderAppVue />
    <JumboAppVue />

  </div>
</template>

<style lang="scss">
@use "./styles/general.scss" as *;

.ciao {
  background-color: aquamarine;
}
</style>
