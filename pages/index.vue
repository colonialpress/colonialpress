<template>
  <div class="LandingPage">
    <Nav />
    <br>
    <Landing />
    <br>
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Landing from '~/components/Landing.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Nav,
    Landing,
    Footer
  }
}
</script>

<style>
</style>
