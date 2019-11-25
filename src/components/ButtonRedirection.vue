<template>
  <form target="_blank" v-bind:action="url">
    <input class="btn btn-dark" type="submit" value="Clique ici pour aller sur mon github" />
  </form>
</template>
<script>
  export default {
    name: "ButtonRedirection"
  }
</script>
<style>

</style>
