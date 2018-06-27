<template>
  <div id="app">
    <TopNav></TopNav>
    <router-view/>
  </div>
</template>

<script>
import TopNav from "./components/topNav/topNav.vue";
export default {
  name: 'App',
    components: {
    TopNav
  }
}
</script>

<style>

</style>
