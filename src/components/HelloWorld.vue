<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <main>
    <h1>{{ msg }}</h1>

    <p>
      Recommended IDE setup:
      <a href="https://code.visualstudio.com/" target="_blank">VSCode</a>
      +
      <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    </p>

    <p>
      <a href="https://vitejs.dev/guide/features.html" target="_blank">
        Vite Documentation
      </a>
      |
      <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
    </p>

    <button type="button" @click="count++">count is: {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>
  </main>
</template>

<style scoped>
@import url("https://use.typekit.net/ijl4xlv.css");
main {
  margin-left: 250px;
  margin-right: auto;
  font-family: proxima-nova,sans-serif;
}
a {
  color: #42b983;
}
</style>
