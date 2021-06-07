<template>
  <div id="app">

    <Header />
    <Main />
    <Panel-menu />

  </div>

</template>

<script>
import Header from './components/header.vue';
import Main from './components/main.vue'
import PanelMenu from './components/panel-menu.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    PanelMenu
  }
}
</script>

<style lang="scss">
  @import './style/general.scss'
</style>
