<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Projects</b-nav-item>
          <b-nav-item href="#">The Team</b-nav-item>
          <b-nav-item href="#">Schedule</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">
            <span style="font-size: 2em; line-height: 20px;"><i class="fab fa-github"></i></span>
          </b-nav-item>
          <b-nav-item href="#">
            <span style="font-size: 2em; line-height: 20px;"><i class="fab fa-facebook"></i></span>
          </b-nav-item>
          <b-nav-item href="#">
            <span style="font-size: 2em; line-height: 20px;"><i class="fab fa-snapchat"></i></span>
          </b-nav-item>
          <b-nav-item href="#">
            <span style="font-size: 2em; line-height: 20px;"><i class="fab fa-instagram"></i></span>
          </b-nav-item>
          <b-nav-item href="#">
            <span style="font-size: 2em; line-height: 20px;"><i class="fab fa-youtube"></i></span>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>  
</template>

<script>
  export default {
    name: 'navbar'
  }
</script>

<style>
</style>