<template>
  <div>
    <b-navbar  fixed="top" variant="faded" type="light" class="bg-white">
      <b-navbar-brand tag="h1" href="#" class="mb-0">Hard to stop.</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- <b-navbar-nav>
          <b-nav-item href="#">Link</b-nav-item>
          <b-nav-item href="#" disabled>Disabled</b-nav-item>
        </b-navbar-nav> -->

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#home">Home</b-nav-item>
          <b-nav-item href="#statistics">Statistics</b-nav-item>
          <b-nav-item href="#info">Information</b-nav-item>
          <b-nav-item href="#helpline">Helpline</b-nav-item>
          <b-nav-item href="#shatterproof">Shatterproof</b-nav-item>

          

          
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  // props: {
  //   msg: String
  // }
}
</script>

