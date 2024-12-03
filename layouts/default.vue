<!-- layouts/default.vue -->
<template>
  <div>
    <header>
      <h1>My Nuxt App</h1>
      <nav>
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
      </nav>
    </header>
    
    <main>
      <Nuxt />
    </main>

    <footer>
      <p>© 2024 My Nuxt App</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
};
</script>

<style scoped>
header, footer {
  background: #333;
  color: white;
  padding: 1rem;
}
nav {
  display: flex;
  gap: 1rem;
}
main {
  padding: 2rem;
}
</style>
