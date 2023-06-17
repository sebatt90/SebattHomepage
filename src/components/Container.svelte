<script lang="ts">
  import Cards from "./Cards.svelte";
  import Grid from "./Grid.svelte";
</script>

<main>
  <div id="container">
    <h1>Hi i'm sebatt90!</h1>
    <p>This is my website, this is a work in progress for now.</p>
    <p>Here are some of my projects:</p>

    <Grid />
  </div>
</main>

<style>
  #container {
    padding-top: 1rem;
    padding-left: 10rem;
    padding-right: 10rem;
  }

  h1 {
    font-size: 2rem;
  }

  p {
    font-size: 1rem;
  }
</style>
