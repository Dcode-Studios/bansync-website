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
.button {
  color: rgb(255, 255, 255);
  text-decoration:none;
  border: 10px solid rgb(109, 109, 109);
  background-color: rgb(109, 109, 109);
  border-radius: 5px;
  margin: 20px;
  text-align: center;
  margin-left: auto;
  margin-right:auto;
  display: block;
  max-width: fit-content;
  cursor: pointer;
}
</style>
