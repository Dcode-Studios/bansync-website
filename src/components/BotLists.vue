<template>
<br>
<div class="intro">
  <h3>⬆️ Bot Lists</h3>
</div>
<div>
    <a href="https://top.gg/bot/743234197484994610">
    <img alt="Failed to load top.gg widget" src="https://top.gg/api/widget/743234197484994610.svg">
    </a>
    <a href="https://botsfordiscord.com/bot/743234197484994610">
    <img title="BanSync on Bots for Discord!" alt="Failed to load BFD widget" src="https://botsfordiscord.com/api/bot/743234197484994610/widget">
    </a>
    <a href="https://discord.boats/bot/743234197484994610">
    <img title="BanSync on Discord Boats!" alt="Failed to load Discord Boats widget" src="https://discord.boats/api/widget/743234197484994610">
    </a>
</div>
</template>

<script>
export default {
  name: 'BotLists'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.intro {
  color: #42b983;
  text-align: center;
}
img {
  opacity: 1;
  animation: fadeIn 1s ease;
  margin: 4px;
  max-width: 300px;
}
@keyframes fadeIn{
  0%{
    opacity: 0;
    }
    100%{
      opacity: 1;
    }
}
div {
  margin-left: auto;
  margin-right: auto;
  text-align: center;
  padding: 2px;
}
</style>
