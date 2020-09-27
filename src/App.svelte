<script>
</script>

<style>
  main {
    max-width: 1440px;
    margin: 0 auto 0 auto;
    display: flex;
    height: 100vh;
    background-color: black;
  }
  .cont {
    flex: 1;
  }

  .right {
    overflow: scroll;
  }
  .hide_scroll::-webkit-scrollbar {
    display: none;
  }

  .hide_scroll {
    -ms-overflow-style: none;
    scrollbar-width: none;
  }
  .padded_box {
    padding: 12px;
  }
  .padded_box_double {
    padding: 24px;
  }
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-column-gap: 20px;
    grid-row-gap: 20px;
    justify-items: stretch;
    align-items: stretch;
  }
  .card {
    background-color: grey;
    height: 300px;
  }
  h1 {
    font-size: 3.5em;
  }
</style>

<main>
  <div class="cont left">
    <div class="padded_box">
      <h1>Hello,<br /> I’m Tushar Debnath.</h1>
      <p>
        I’m a Product designer from New Delhi, India. I am currently working at
        Zomato as a Senior Product Designer .
      </p>
    </div>
  </div>
  <div class="cont right hide_scroll">
    <div class="padded_box_double grid">
      <div class="card" />
      <div class="card" />
      <div class="card" />
      <div class="card" />
    </div>
    <div class="padded_box_double grid">
      <div class="card" />
      <div class="card" />
      <div class="card" />
      <div class="card" />
    </div>
  </div>
</main>
