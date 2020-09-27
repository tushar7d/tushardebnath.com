<script>
</script>

<style>
 
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
 
</style>


 
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

