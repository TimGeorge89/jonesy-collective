<template>
  <div id="app">
    <Navigation></Navigation>
    <router-view/>
    <Footer></Footer>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Footer from '@/components/Footer'

export default {
  data() {
    return {

    }
  },
  components: {
    Footer,
    Navigation
  }
}
</script>

<style lang="scss">

</style>


