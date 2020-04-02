<template>
  <b-navbar class="mb-3" toggleable="lg" type="dark" sticky>
    <b-container>
      <b-navbar-brand href="#">SiteName</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Health</b-nav-item>
          <b-nav-item href="#">Fitness</b-nav-item>
          <b-nav-item href="#">Sports</b-nav-item>
          <b-nav-item href="#">Diet</b-nav-item>
      </b-navbar-nav>
    </b-container>
  </b-navbar>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style>
.navbar {
  background-color: #563d7c;
  box-shadow: 0 8px 17px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}
</style>
