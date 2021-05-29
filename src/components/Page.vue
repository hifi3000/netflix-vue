<template>
  <div>
    <Menu />
    <Navigation />
    <Main />
  </div>
</template>

<script>
import Menu from './Menu.vue'
import Navigation from './Navigation.vue'
import Main from './Main.vue'

export default {
  name: 'HelloWorld',
  components: {
    Menu,
    Navigation,
    Main
  }
}
</script>

<style>

</style>