<script >
import AppHeaderNav from './components/AppHeaderNav.vue'
import AppMain from './components/AppMain.vue';
import AppIcons from './components/AppIcons.vue';


export default {
  components: {
    AppHeaderNav,
    AppMain,
    AppIcons,
  }
}
</script>



<template>
  <AppHeaderNav />
  <div id="mainContent">
    <AppMain />

  </div>
  <div id="icons">
    <AppIcons />
  </div>
</template>

<style scoped>
#mainContent {
  background-color: black;
}

#icons {
  background-color: #0282f9;
}
</style>
