<!-- Comment -->
<!-- Comment -->
<!-- Comment -->
<template>
  <div id="app">
    <Header />
    <div id="content" class="content">
      <router-view></router-view>
    </div>
  </div>
</template>

<!-- Comment -->
<!-- Comment -->
<!-- Comment -->
<script>
import Header from "./components/layout/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<!-- Comment -->
<!-- Comment -->
<!-- Comment -->
<style>
</style>

