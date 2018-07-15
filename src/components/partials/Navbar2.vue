<template>
  <div uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky; bottom: #transparent-sticky-navbar">
  <vk-navbar>

  <vk-navbar-nav>
    <a class="uk-navbar-toggle" href="#">
            <span uk-navbar-toggle-icon></span> <span class="uk-margin-small-left">Do</span>
        </a>
        <div uk-dropdown="mode: click">
        <ul class="uk-nav uk-dropdown-nav">
        <li class="uk-active"><a href="#">Guides</a></li>
        <li><a href="#">Opportunities</a></li>
        <li><a href="#">Universities</a></li>
        <li class="uk-nav-divider"></li>
        <li><a href="#">Competitions</a></li>
        <li><a href="#">Courses</a></li>
        </ul>
        </div>
    <vk-navbar-nav-item title="My courses" href="/"></vk-navbar-nav-item>
  </vk-navbar-nav>
  <a href="/#/" slot="center"><img class="uk-width-1-2@s" src="@/assets/logo.png"></a>

  <vk-navbar-nav slot="right">
    <vk-navbar-nav-item title="Friends" href="/" active></vk-navbar-nav-item>
    <a class="uk-navbar-item" href="#" uk-icon="bell"></a>
    <a class="uk-navbar-toggle" href="#">
            <span uk-navbar-toggle-icon></span> <span class="uk-margin-small-left">Profile</span>
        </a>
        <div uk-dropdown="mode: click">
        <ul class="uk-nav uk-dropdown-nav">
        <li class="uk-active"><a href="/profile">Profile</a></li>
        <li><a href="#">Add guide</a></li>
        <li><a href="#">Edit</a></li>
        <li class="uk-nav-divider"></li>
        <li><a href="/">Log out</a></li>
        </ul>
        </div>
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