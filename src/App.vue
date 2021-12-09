<template>
  <div id="app">
    <header>
       <Header />
    </header>
    <main>
       <WelcomeToAvadaHealth />

    </main>


   <Footer />

  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import WelcomeToAvadaHealth from '@/components/WelcomeToAvadaHealth.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'App',
  components: {
   Header,
   WelcomeToAvadaHealth,
   Footer,
  }
}
</script>

<style lang="scss">
@import '@/styles/globals';
@import '@/styles/utilities';

</style>
