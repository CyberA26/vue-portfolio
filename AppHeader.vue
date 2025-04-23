<template>
  <header class="app-header">
    <nav>
      <router-link to="/" exact-active-class="active">Home</router-link>
      <router-link to="/about" exact-active-class="active">About</router-link>
    </nav>
  </header>
</template>

<script>
export default{
  name: 'AppHeader'
}
</script>

<style scoped>
.app-header {
  background-color: #f4f4f4;
  padding: 10px 20px;
  border-bottom: 1px solid #ccc;
}
nav {
  display: flex;
  gap: 20px;
}

.router-link-active, .active {
  font-weight: bold;
  color: #42b983;
  text-decoration: underline;
}
</style>