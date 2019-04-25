<template>
  <div id="home-page">
    <TheHeader />
    <Hero />
    <Credibility />
  </div>
</template>

<script>
import TheHeader from '~/components/TheHeader';
import Hero from '~/components/Hero';
import Credibility from '~/components/Credibility';
export default {
  name: 'HomePage',
  components: {
    TheHeader,
    Hero,
    Credibility
  }

}
</script>

<style>

</style>
