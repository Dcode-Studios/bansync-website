<template>
<div class="intro">
  <br>
  <h3>🛠 Team Members</h3>
  <ol id="teamList">
    <li v-for="item in members" :key="item.message">
      <a v-bind:href="`${item.href}`">
        <div class="teamUserBox">
        <img v-bind:src="`${item.icon}`" id="teamUserPfp">
        <br>
        <a><b>{{item.name}}</b></a>
        </div>
      </a>
      <br>
    </li>
  </ol>
</div>
<br>
</template>

<script>
export default {
  name: 'TeamMembers',
    data() {
    return {
      members: require("../assets/team.json")
    }
  }
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
  min-width: 100px;
}
.teamUserBox {
  border: white solid 1px;
  padding: 5px;
  color: white;
  text-decoration: none;
  max-width: fit-content;
  margin-right: auto;
  margin-left: auto;
  min-width: 200px;
  transition: transform .2s; /* Animation */
}
.teamUserBox:hover {
  background-color: rgb(51, 51, 51);
  border: #42b983 solid 1px;
  box-shadow: 0 0 10px rgb(255, 255, 255);
  transform: scale(1.1);
}
:link {
  text-decoration: none;
  cursor:pointer;
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
