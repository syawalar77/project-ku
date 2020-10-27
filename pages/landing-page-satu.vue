<template>
  <div>
    <NavbarSection/>
    <JumbotronSection/>
    <SignInSection/>
  </div>
</template>

<script>
import NavbarSection from '~/components/landingPage-satu/NavbarSection.vue'
import JumbotronSection from '~/components/landingPage-satu/JumbotronSection.vue'
import SignInSection from '~/components/landingPage-satu/SignInSection.vue'

export default {
  components: {
    NavbarSection: NavbarSection,
    JumbotronSection: JumbotronSection,
    SignInSection: SignInSection,
  }

}
</script>

<style>

</style>