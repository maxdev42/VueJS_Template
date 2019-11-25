<template>
  <div class="home">
    <br><br>
    <h2>Bienvenu sur mon template de site avec VueJS</h2>
    <div>
      <p>
        Ici vous retrouverez plusieurs composants utilisants différentes méthodes de VueJS ainsi que de Boostrap et jQuery.
      </p>
      <form target="_blank" v-bind:action="url">
          <input class="btn btn-dark" type="submit" value="Clique ici pour aller sur mon github" />
      </form>
    </div>
    <div>
      <Card/>
    </div>
  </div>
</template>
<script>
import Card from "./Card"

export default {
  name: 'Home',
    components: {
    Card
  },
  data() {
    return {
      url: "https://github.com/maxdev42/"
    }
  }
}
</script>
<style>
  
</style>
