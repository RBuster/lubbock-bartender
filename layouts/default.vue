<template>
  <div>
    <NavBar />
    <Nuxt />
    <FooterComponent />
  </div>
</template>
<script>
import NavBar from '~/components/navBar.vue'
import FooterComponent from '~/components/footer.vue'
export default {
  name: 'DefaultLayout',
  components: {
    NavBar,
    FooterComponent
  }
}
</script>
