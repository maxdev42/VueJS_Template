<template>
  <div class="card" style="width: 18rem;">
  <img src="https://www.competencephoto.com/photo/art/grande/31056991-29406133.jpg?v=1553260189" class="card-img-top">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
</template>
<script>
  export default {
    name: "Card",
    props: ['article'],

  data() {
    return {
       url: "https://github.com/maxdev42"
    }
  }
}

</script>
<style>

</style>
