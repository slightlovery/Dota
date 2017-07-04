<template>
  <div id="app">
    <vue-header></vue-header>
    <router-view></router-view>
    <vue-footer></vue-footer>
  </div>
</template>

<script>
  import header from './components/header.vue'
  import footer from './components/footer.vue'

  export default {
    name: 'app',
    components: {
      VueHeader: header,
      VueFooter: footer
    }
  }
</script>
