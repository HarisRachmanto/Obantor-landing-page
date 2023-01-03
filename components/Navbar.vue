<template>
  <div>
    <b-navbar toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="#" style="margin-left: 70px"><b>Obantor</b></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#"><b>Home</b></b-nav-item>
          <b-nav-item href="#"><b>Features</b></b-nav-item>
          <b-nav-item href="#"><b>FAQ</b></b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav class="ml-auto">
            <b-nav-form>
              <b-button pill variant="outline-info" style="margin-right: 70px">Download Now</b-button>
            </b-nav-form>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <hr />
  </div>
</template>

<script>
export default {}
</script>

<style>

</style>