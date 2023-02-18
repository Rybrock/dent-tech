<template>
    <app-navbar/>
    <app-u-s-p-bar/>
    <router-view/>
    <app-footer/>
</template>

<script>
import AppNavbar from '../src/components/AppNavbar.vue'
import AppFooter from '../src/components/AppFooter.vue'
import AppUSPBar from '../src/components/AppUSPBar.vue'



export default {
  components: {
    AppNavbar,
    AppFooter,
    AppUSPBar
  },
}

</script>

<style>
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #221B1B;

}
</style>
