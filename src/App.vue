<template>
  <div id="app">
    <!--
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>-->
      <!-- Image and text -->
  <b-navbar type="dark" variant="info" class="mb-5">
    <b-navbar-brand href="#" class="customnav-brnd">
      <img src="/logo.jpg" width="40px" height="40px" class="d-inline-block align-top" alt="Logo">
      BanSync
    </b-navbar-brand>
    <b-navbar-nav class="ml-auto">
        <b-nav-item class="button" href="https://discord.com/oauth2/authorize?client_id=743234197484994610&permissions=347328&scope=applications.commands%20bot">Invite the Bot</b-nav-item>
        <b-nav-item href="https://bansync.dcode.site/privacy_policy.pdf">Privacy Policy</b-nav-item>
      </b-navbar-nav>
  </b-navbar>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #2c3e50;
  height: 100%;
  width: 100vw;
  margin: 0;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.customnav-brnd {
  font-size: 1.7rem;
}
.navbar {
  padding: .2rem .5rem;
}
</style>
