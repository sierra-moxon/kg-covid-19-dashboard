<template>

  <b-navbar id="dash-navbar" class="fixed-top" type="dark" variant="info" fixed="true" toggleable="sm">

    <b-navbar-brand to="/">Translator Testing Dashboard Demo</b-navbar-brand>

    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item
          href="https://biolink.github.io/biolink-model/docs/"
          target="_blank"
        >
          <font-awesome-icon :icon="['fas', 'home']"/>
        </b-nav-item>

        <b-nav-item
          href="https://github.com/TranslatorSRI/translator-testing-dashboard-demo"
          target="_blank"
        >
          <font-awesome-icon :icon="['fab', 'github']"/>
        </b-nav-item>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>

</template>

<script>

export default {
  name: 'Navbar',
};

</script>

<style lang="scss">
  @import "~@/style/variables";

  #dash-navbar {
    height: $navbar-height;
  }
  .bg-info {
    background-image: -webkit-linear-gradient(left, #0B556B 0%, #232733 100%) !important;
    background-image: linear-gradient(to right, #0B556B 0%, #232733 100%) !important;
    background-repeat: repeat-x !important;
    box-shadow: 0 2px 1px -1px rgba(0,0,0,.2), 0 1px 1px 0 rgba(0,0,0,.14), 0 1px 3px 0 rgba(0,0,0,.12);
  }
</style>
