<template>
  <body>
    <headerMain />
    <underMainWrapper />
    <footerWrapper />
  </body>
  
</template>

<script>
import headerMain from './components/headerMain.vue'
import underMainWrapper from './components/underMainWrapper.vue'
import footerWrapper from './components/footerWrapper.vue'

export default {
  name: 'App',
  components: {
    headerMain,
    underMainWrapper,
    footerWrapper
  }
}
</script>

<style>
body {
  margin: 0;
}
</style>
