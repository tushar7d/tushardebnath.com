<script>
  import Grid from "./Components/Grid.svelte";
  import About from "./Components/About.svelte";
</script>

<style>
  main {
    max-width: 1280px;
    margin: 0 auto 0 auto;
    display: flex;
    height: 100vh;
    background-color: black;
  }
</style>

<main>
  <About />
  <Grid />
</main>
