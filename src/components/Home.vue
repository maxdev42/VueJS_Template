<template>
  <div class="home">
    <br>
    <h2>Bienvenu sur mon template de site avec VueJS</h2>
    <div>
      <p>
        Ici vous retrouverez plusieurs composants utilisants différentes méthodes de VueJS ainsi que de Boostrap et jQuery.
      </p>
      <ButtonRedirection/>
    </div>
    <div>
      <Card id="card"/>
    </div>
  </div>
</template>
<script>
import Card from "./Card"
import ButtonRedirection from "./ButtonRedirection"

export default {
  name: 'Home',
  components: {
    Card,
    ButtonRedirection
  }

}
</script>
<style>
  #card {
    margin : 20px;
  }
</style>
