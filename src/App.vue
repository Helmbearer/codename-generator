<template>
  <div class="main">
    <name-generator/>
  </div>
</template>

<script>

import NameGenerator from './components/NameGenerator.vue'

export default {
  name: 'App',
  components: {
    NameGenerator
  }
}
</script>

<style>
.main {
    display: flex;
    justify-content:center;
    align-items: center;
    flex-direction: column;
    height: 100%;
    width: 100%;
  }
</style>
