<template>
  <!-- COMPANY NAME: FrontEnd Firepower -->
  <!-- SLOGAN: Unleashing the Web's Full Potential with FrontEnd Firepower! -->
  <body>
    <!-- <NavBar /> -->
    <HamburgerOverlay />
  </body>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'

// import NavBar from '../components/NavBar.vue'
import HamburgerOverlay from '../components/HamburgerOverlay.vue'

export default {
  name: 'IndexPage',

  components: {
    // NavBar,
    HamburgerOverlay,
  },
}
</script>
