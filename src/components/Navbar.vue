<template>
  <nav class="blue darken-3">
    <div class="nav-wrapper ">
      <router-link to="/" class="brand-logo">Tasks</router-link>
      <ul class="right hide-on-med-and-down">
        <router-link
         to="/"
         exact
         active-class="active"
         tag="li">
            <a href="#">Create</a>
        </router-link>
        <router-link
            to="/list"
            exact
            active-class="active"
            tag="li">
            <a href="#">List</a>
        </router-link>
      </ul>
    </div>
  </nav>
</template>

<script>
    export default {
        name: 'Navbar'
    }
</script>

<style lang="scss" scoped>
    nav {
        padding: 0 2rem;
    }
</style>