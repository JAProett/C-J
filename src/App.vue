<template>
  <q-layout view="hHh lpR fFf">
    <TopNav/>
    <q-page-container>
      <HelloWorld />
    </q-page-container>
  </q-layout>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TopNav from './components/TopNav.vue'

export default {
  name: 'LayoutDefault',

  components: {
    HelloWorld,
    TopNav
  },

  data () {
    return {
      leftDrawerOpen: false
    }
  }
}
</script>

<style>
</style>
