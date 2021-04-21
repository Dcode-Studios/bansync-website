<template>
<div class="intro">
  <h3>About BanSync</h3>
  <p>
    BanSync is a Discord bot that can be used to:
    <ol>
      <li>📝 Be notified of joining users who've been banned from other servers.</li>
      <li>🔁 Sync Bans between your servers</li>
    </ol>
    </p>
    <h4>🔁 Linked Servers</h4>
    <p>
      Linked Servers is a feature BanSync has to allow you to link up your servers to have bans synced within them. This means that if someone gets banned from one of the servers, they'll automatically be banned and blacklisted from all the linked servers.
    </p>
</div>
</template>

<script>
export default {
  name: 'Intro'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.intro {
  color: #42b983;
  text-align: center;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
}
</style>
