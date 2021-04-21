<template>
<br>
<div>
  <div class="intro">
    <h3>/ Slash Commands</h3>
    <p>BanSync has work in progress Slash Commands, but more are to come!</p>
  </div>
  <img src="../assets/slash_commands.png">
</div>
</template>

<script>
export default {
  name: 'SlashCommands'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  opacity: 1;
  animation: fadeIn 1s ease;
  margin: 4px;
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
.intro {
  color: rgb(170, 173, 176);
  text-align: center;
}
.intro p {
  color: #42b983;
  text-align: center;
}
img {
  max-width: 75%;
  min-width: 300px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
