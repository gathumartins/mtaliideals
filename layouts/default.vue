<template>
  <div>
    <navbar />
    <nuxt />
    <foot />
  </div>
</template>

<style>

</style>
<script>
import Navbar from '~/components/Navbar.vue'
import Foot from '~/components/Footer.vue'
export default {
   components: {
    Navbar,
    Foot
  }
}
</script>

