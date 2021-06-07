<template>

  <div id="app">

    <Header />
    <Main />
    <Panel />
    <Footer />

  </div>

</template>

<script>
import Header from './components/header.vue';
import Main from './components/main.vue'
import Panel from './components/panel.vue';
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Panel,
    Footer
  }
}
</script>

<style lang="scss">
  @import './style/general.scss';

</style>
