<template>
  <m-header></m-header>
  <tab></tab>
  <router-view></router-view>
  <player></player>
</template>

<script>
import Header from './components/header/header'
import Tab from './components/tab/tab'
import player from './components/player/player'

export default {
  components: {
    MHeader: Header,
    Tab,
    player
  }
}
</script>

<style lang="scss">
</style>
