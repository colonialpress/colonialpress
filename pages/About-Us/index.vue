<template>
  <div class="AboutPage">
    <Nav />
    <Soon />
    <Footer />
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Footer from '~/components/Footer.vue'
import Soon from '~/components/Coming-Soon.vue'

export default {
  components: {
    Nav,
    Footer,
    Soon
  }
}
</script>

<style>
</style>
