<template>
  <div id="app">
    <Sidebar />
    <Resources />
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Resources from './components/Resources.vue'
export default {
  name: 'App',
  components: {
    Sidebar,
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
