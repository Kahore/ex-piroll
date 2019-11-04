<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">
    <img alt="brand logo" src="@/assets/logo.svg">
  </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div
    class="collapse navbar-collapse"
    id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <router-link
          class="nav-link"
          to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link
          class="nav-link"
          to="/about">About</router-link>
      </li>
      <li class="nav-item">
        <router-link
          class="nav-link"
          to="/contact">Contact</router-link>
      </li>

    </ul>

  </div>
</nav>

</template>

<script>
export default {
  name: 'AppNavbar'
}
</script>

<style lang="scss" scoped>
.router-link-exact-active{
  color:#10c9c3!important;
}
</style>
