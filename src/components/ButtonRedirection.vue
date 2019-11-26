<template>
  <form target="_blank" v-bind:action="url">
    <input class="btn btn-dark" type="submit" value="Clique ici pour aller sur mon github" />
  </form>
</template>
<script>
  export default {
    name: "ButtonRedirection",

    data() {
      return {
        url: "https://github.com/maxdev42"
      }
    }
  }
</script>
<style>

</style>
