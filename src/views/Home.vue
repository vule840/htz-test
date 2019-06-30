<template>
  <div class="home">
  	<Carusel/>
    <img alt="Vue logo" src="../assets/logo.png">
 <!--    <svg class="htz_logo"><use xlink:href="images/sprite-sheet.svg#htz_home_logo" /></svg> -->

  <!--    <svg class="htz_logo"><use xlink:href="prijava_gumb.svg
  " /></svg> -->

    <!-- <img alt="Vue logo" src="prijava_gumb.svg"> -->
<!-- <svg class="tanjur"><use xlink:href="/images/sprite-sheet.svg#htz_home_logo
  " /></svg> -->
<!-- <svg v-svg
     symbol="hrvlogo"
     size="0 0 24 24"
     role="presentation"
     class="icon--inline"
></svg> -->
     
    <HelloWorld msg="Welcome to Your Vue.js App"/>


  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Carusel from '@/components/Carusel.vue'


// import SvgSprite from 'vue-svg-sprite';
 
// Vue.use(SvgSprite);
// import VueLogo from './public/vue.svg'

export default {
  name: 'home',
  components: {
    HelloWorld,
    Carusel,
    // VueLogo
  },
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
}
</script>
