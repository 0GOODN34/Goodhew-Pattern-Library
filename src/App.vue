<template>
  <div id="app">
    <Page/>
  </div>
</template>

<script>
import Page from './components/page.vue'

export default {
  name: 'app',
  components: {
    Page
  }
}
</script>

<style>
@media (min-width: 768px) {
#app {
  padding-top: 75px;
}
}



</style>
