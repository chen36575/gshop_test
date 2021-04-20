<template>
  <div id="app">
    <router-view />
    <footer-guide v-show="$route.meta.showFooter === true"/>
  </div>
</template>

<script>
import FooterGuide from './components/FooterGuide/FooterGuide'

export default {
  components: {
    FooterGuide
  }
}
</script>

<style>

</style>
