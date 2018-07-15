<template>
  <div uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky; bottom: #transparent-sticky-navbar">
  <vk-navbar>

  <vk-navbar-nav>
    <vk-navbar-nav-item title="About us" href="/aboutus" active></vk-navbar-nav-item>
    <vk-navbar-nav-item title="Contacts" href="/contacts"></vk-navbar-nav-item>
  </vk-navbar-nav>
  <a href="/#/" slot="center"><img class="uk-width-1-2@s" src="@/assets/logo.png"></a>

  <vk-navbar-nav slot="right">
    <vk-navbar-nav-item title="Sign up" href="/register" active></vk-navbar-nav-item>
    <vk-navbar-nav-item title="Account" href="/login"></vk-navbar-nav-item>
  </vk-navbar-nav>

</vk-navbar>
</div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .uk-navbar-container:not(.uk-navbar-transparent) {
    background: #ffffff;
}
</style>