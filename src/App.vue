<template>
  <div id="app">
    <Sidebar />
    <CenterTop />
    <Resources />
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import CenterTop from './components/CenterTop.vue'
import Resources from './components/Resources.vue'
export default {
  name: 'App',
  components: {
    Sidebar,
    CenterTop,
    Resources,

  }
}
</script>

<style>
#app {
 
  
}

@font-face {
  font-family: SofiaProBlack;
  src: url(fonts/SofiaProBlack.ttf);
}
@font-face {
  font-family: SofiaProSemiBold;
  src: url(fonts/SofiaProSemiBold.ttf);
}
</style>
