<template>
<div class="intro">
  <br>
  <h3>ℹ️ Other Resources</h3>
  <ol>
    <li><a href="/privacy_policy.pdf">Privacy Policy</a></li>
    <br>
    <li><a href="https://github.com/TechGeekGamer">Main Developer's GitHub (TechGeekGamer)</a></li>
  </ol>
</div>
<br>
</template>

<script>
export default {
  name: 'OtherResources'
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
a {
  color: rgb(255, 255, 255);
  text-decoration:none;
  border: 10px solid rgb(109, 109, 109);
  background-color: rgb(109, 109, 109);
  border-radius: 5px;
  margin: 20px;
}
a :hover {
  background-color: rgba(109, 109, 109, .5);
}
ol {
  list-style: none;
  padding-left: 0px;
}
</style>
