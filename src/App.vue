<template>
  <div id="app">
    <div>
      <Header class="navbar"/>
    </div>
    <Home/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";

export default {
  name: 'app',
  components: {
    Header,
    Home
  }
}
</script>

<style>

</style>
