<template>
  <header>
    <router-link to="/">
      <h1><span>Shoppies </span>Movie Award</h1>
    </router-link>
  </header>
   <main>
      <router-view/>
   </main>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style lang="scss" scoped>

</style>
