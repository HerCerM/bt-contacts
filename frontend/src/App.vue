<template>
  <div id="app">
    <main class="mt-12 mx-auto mb-20 lg:px-36 px-4 container">
      <router-view />
    </main>
  </div>
</template>

<script>
export default {
  name: "App",

  metaInfo: {
    title: "Contacts app"
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
