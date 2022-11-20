<script>

import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue';
import AppMain from './components/AppMain.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    AppMain
  }
}
</script>

<template>
  

  <AppHeader/>
  <AppFooter/>
  <AppMain/>
</template>


<style lang="scss">
  @use './style/general';
</style>
