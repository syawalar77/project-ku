<template>
  <div class="container">
      <NavbarSection/>
      <AboutSection/>
  </div>
</template>

<script>
import NavbarSection from '~/components/landingPage-satu/NavbarSection.vue'
import AboutSection from '~/components/landingPage-satu/AboutSection.vue'

export default {
    components: {
        NavbarSection: NavbarSection,
        AboutSection: AboutSection,
    }

}
</script>

<style>

</style>