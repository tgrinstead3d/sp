<script setup>
import SideNav from './components/SideNav.vue'
import TopNav from './components/TopNav.vue'
</script>

<template>
  <div id="app">
    <SideNav/>
    <TopNav/>
  </div>
</template>

<style>
@import url("https://use.typekit.net/ijl4xlv.css");
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
body {
  font-family: proxima-nova,sans-serif;
  max-width: 1920px;
  margin-inline: auto;
}
</style>
