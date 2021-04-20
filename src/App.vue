<template>
  <Intro/>
  <BotLists/>
  <SlashCommands/>
</template>

<script>
import Intro from './components/Intro.vue'
import BotLists from './components/BotLists.vue'
import SlashCommands from './components/SlashCommands'

export default {
  name: 'App',
  components: {
    Intro,
    BotLists,
    SlashCommands
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body {
    background-color: black;
}
</style>
