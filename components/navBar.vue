<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="/" exact>
        NavBar
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/about" exact>
            About
          </b-nav-item>
          <b-nav-item href="/gallery" exact disabled>
            Gallery
          </b-nav-item>
          <b-nav-item href="/contact" exact>
            Contact
          </b-nav-item>
          <b-nav-item href="/partners" exact disabled>
            Partners
          </b-nav-item>
          <!-- <b-nav-item href="#" disabled>
            Disabled
          </b-nav-item> -->
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <!-- <b-navbar-nav class="ml-auto">

        </b-navbar-nav> -->
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>
