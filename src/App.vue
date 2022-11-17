<script >
import TopInfoVue from './components/TopInfo.vue';
import HeaderAppVue from './components/HeaderApp.vue';

export default {
  components: {
    TopInfoVue,
    HeaderAppVue,

  }
}
</script>

<template>
  <TopInfoVue />
  <div class="ciao">
    <HeaderAppVue />

  </div>
</template>

<style lang="scss">
@use "./styles/general.scss" as *;

.ciao {
  background-color: aquamarine;
}
</style>
