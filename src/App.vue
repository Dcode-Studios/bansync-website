<template>
  <Intro/>
  <About/>
  <SlashCommands/>
  <TeamMembers/>
  <BotLists/>
  <OtherResources/>
</template>

<script>
import Intro from './components/Intro.vue'
import BotLists from './components/BotLists.vue'
import SlashCommands from './components/SlashCommands'
import About from './components/About'
import OtherResources from './components/OtherResources'
import TeamMembers from './components/TeamMembers'

export default {
  name: 'App',
  components: {
    Intro,
    BotLists,
    About,
    SlashCommands,
    OtherResources,
    TeamMembers
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 15pt;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body {
    background-color: black;
}
</style>
