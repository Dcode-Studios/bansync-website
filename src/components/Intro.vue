<template>
  <div class="hello">
    <img src="../assets/logo.png" class="logo">
    <div class="intro">
      <h1 style="color: #42b983;">BanSync</h1>
      <h4 id="topmsg">Help keep out possible troublemakers from your server by knowing user's previous bans, or by linking your servers together to sync bans within them.</h4>
    </div>
    <img class="bansync_helpmenu" src="../assets/bansync_help_menu.png">
    <a class="button" href="https://discord.com/oauth2/authorize?client_id=743234197484994610&permissions=347328&scope=applications.commands%20bot">Invite bot</a>
  </div>
</template>

<script>
export default {
  name: 'Intro'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#topmsg {
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
}
.intro {
  color: #ffffff;
  text-align: center;
}
.logo {
  min-width: 150px;
  width: 10%;
  height: 10%;
  border-radius: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.bansync_helpmenu {
  width: 40%;
  height: 40%;
  min-width: 250px;
  max-width: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
