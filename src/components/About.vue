<template>
<div class="intro">
  <h3 style="color: #42b983;">About BanSync</h3>
  <p>
    BanSync is a Discord bot that can be used to:
    <ol>
      <li>📝 Be notified of joining users who've been banned from other servers.</li>
      <li>🔁 Sync Bans between your servers</li>
    </ol>
    </p>
    <h4 style="color: #42b983;">🔁 Linked Servers</h4>
    <p>
      Linked Servers is a feature BanSync has to allow you to link up your servers to have bans synced within them. This means that if someone gets banned from one of the servers, they'll automatically be banned and blacklisted from all the linked servers.
    </p>
    <h4 style="color: #42b983;">📝 Global Ban Reason Database</h4>
    <p>
      BanSync has a feature that tracks bans you make, and shares information about it to other servers. This feature is <b>optional</b> and is <b><a style="color: red;">disabled</a> by default</b>. This can be <a style="color: green;">enabled</a>/<a style="color: red;">disabled</a> via the <code>&settings</code> command.
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
  color: #ffffff;
  text-align: center;
  max-width: 500px;
  margin-left: auto;
  margin-right: auto;
}
ol {
  list-style:circle;
  padding-left: 0px;
  text-align: left;
}
</style>
