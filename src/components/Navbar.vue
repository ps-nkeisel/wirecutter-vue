<template>
  <b-navbar toggleable="lg" type="light" variant="faded">
    <b-navbar-brand href="#">SiteName</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Health</b-nav-item>
        <b-nav-item href="#">Fitness</b-nav-item>
        <b-nav-item href="#">Sports</b-nav-item>
        <b-nav-item href="#">Diet</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>
