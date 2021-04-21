<template>
<div class="intro">
  <br>
  <h3>🛠 Team Members</h3>
  <ol>
    <li><div class="teamUserBox">
      <img src="../assets/logo.png" id="teamUserPfp">
      <br>
      <a><b>TechGeekGamer</b></a>
      </div></li>
      <br>
  </ol>
</div>
<br>
</template>

<script>
export default {
  name: 'TeamMembers'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#teamUserPfp {
  width: 20%;
  height: 20%;
  padding: 0px;
  margin: 0px;
  border-radius: 50%;
}
.teamUserBox {
  border: white solid 1px;
  padding: 5px;
}
.intro {
  color: #42b983;
  text-align: center;
  max-width: 400px;
  margin-left: auto;
  margin-right: auto;
}
ol {
  list-style: none;
  padding-left: 0px;
}
</style>
