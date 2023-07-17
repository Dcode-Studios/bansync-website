<template>
  <div id="app">
    <b-navbar toggleable="lg" type="dark" variant="info" class="mb-2">
      <b-navbar-brand href="#" class="customnav-brnd">
        <b-avatar width="40px" src="/logo.jpg" alt="Bot Logo" />
        BanSync
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item class="button mx-auto" href="https://discord.gg/Vh9hPTF"
            >Support Server</b-nav-item
          >
          <b-nav-item
            class="button mx-auto"
            href="https://bansync.dcode.site/invite"
            >Invite the Bot</b-nav-item
          >
          <b-nav-item
            class="mx-auto"
            href="https://bansync.dcode.site/privacy_policy.pdf"
            >Privacy Policy</b-nav-item
          >
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <router-view />
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
  padding: 0.2rem 0.5rem;
}
</style>
