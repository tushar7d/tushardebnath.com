<script>
  import Content from "./Components/Content.svelte";
  import Grid from "./Components/Grid.svelte";
</script>

<style>
  .container {
    max-width: 1280px;
    min-width: 320px;
    margin: 0 auto 0 auto;
    display: block;
    
  }
  .grid {
    width: 100%;

  }
  .content {
    width: 100%;
  }
  /* Extra small devices (phones, 600px and down) */
  /*  @media only screen and (max-width: 600px) {
    .container {
      background-color: red;
    }
  }

  /* Small devices (portrait tablets and large phones, 600px and up) 
  @media only screen and (min-width: 600px) {
    .container {
      background-color: pink;
    }
  }
  */

  

  /* Large devices (laptops/desktops, 992px and up) */
  @media only screen and (min-width: 992px) {
    .container {
      display: flex;
      
      height: 100vh;
      overflow: hidden;
    }
    .content {
      width: 50%;
    }
    .grid {
      width: 50%;
      overflow: scroll;
      -ms-overflow-style: none;  /* IE and Edge */
  scrollbar-width: none;  /* Firefox */
    }
    .grid::-webkit-scrollbar {
  display: none;
}
  }

  /* Extra large devices (large laptops and desktops, 1200px and up) */
  @media only screen and (min-width: 1200px) {
    .container {
      width: 100%;
      height: 100vh;
      overflow: hidden;
    }
    .content {
      width: 50%;
    }
    .grid {
      width: 50%;
      overflow: scroll;
      -ms-overflow-style: none;  /* IE and Edge */
  scrollbar-width: none;  /* Firefox */
    }
    .grid::-webkit-scrollbar {
  display: none;
}
  }
</style>

<div class="container">
  <div class="content">
    <Content />
  </div>

  <div class="grid">
    <Grid />
  </div>
</div>
