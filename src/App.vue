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
  border: 15px solid #42b983;
  background-color: #42b983;
  border-radius: 5px;
  margin: 20px;
  text-align: center;
  margin-left: auto;
  margin-right:auto;
  display: block;
  max-width: fit-content;
  cursor: pointer;
  font-size: 20pt;
  transition: transform .2s; /* Animation */
}
.button:hover {
  box-shadow: 0 0 5px rgb(255, 255, 255);
  transform: scale(1.1);
}
.button:active {
  box-shadow: 0 0 7px rgb(255, 255, 255);
  transform: scale(1.2);
}
</style>
