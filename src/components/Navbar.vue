<template>
  <div class="navbar">
    <nav>
      <router-link to="/">Main</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
};
</script>

<style scoped>

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
