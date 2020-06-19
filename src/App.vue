<template>
  <div id="app">
    <Sidebar />
    <CenterTop />
    <Resources />
    <IliustrationRight />
    <RightFooter />
 
    
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import CenterTop from './components/CenterTop.vue'
import Resources from './components/Resources.vue'
import IliustrationRight from './components/IliustrationRight.vue'
import RightFooter from './components/RightFooter.vue'

export default {
  name: 'App',
  components: {
    Sidebar,
    CenterTop,
    Resources,
    IliustrationRight,
    RightFooter,
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
@font-face {
  font-family: SofiaProRegular;
  src: url(fonts/SofiaProRegular.ttf);
}

</style>
