<template>
  <div class="content">
    <navigation />
    <layout class="container" />
  </div>
</template>

<script>
import Navigation from '../../components/Navigation.vue';
import Layout from '../.nuxt/layouts/default'

export default {
  components: {
    Navigation, Layout
  }
}
</script>

<style>
.container {
  background: #2d3436;
}
</style>
