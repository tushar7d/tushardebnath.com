<script>
</script>

<style>
  .container {
    max-width: 1280px;
    min-width: 320px;
    margin: 0 auto 0 auto;
    display: block;
  }
  .grid {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background-color: wheat;
    width: 100%;
    flex: 1;
  }
  .content {
    width: 100%;
  }
  /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 600px) {
    .container {
      background-color: red;
    }
  }

  /* Small devices (portrait tablets and large phones, 600px and up) */
  @media only screen and (min-width: 600px) {
    .container {
      background-color: pink;
    }
  }

  /* Medium devices (landscape tablets, 768px and up) */
  @media only screen and (min-width: 768px) {
    .container {
      background-color: blue;
    }
  }

  /* Large devices (laptops/desktops, 992px and up) */
  @media only screen and (min-width: 992px) {
    .container {
      display: flex;
      background-color: yellow;
      height: 100vh;
    }
    .content {
      width: 50%;
    }
    .grid {
      width: 50%;
    }
  }

  /* Extra large devices (large laptops and desktops, 1200px and up) */
  @media only screen and (min-width: 1200px) {
    .container {
      display: flex;
      background-color: purple;
      width: 100%;
      height: 100vh;
    }
    .content {
      width: 50%;
    }
    .grid {
      width: 50%;
    }
  }
</style>

<div class="container">
  <div class="content">
    <div class="content_top">
      <h1 class="heading">Hello, I’m Tushar Debnath</h1>
      <p class="paragraph">
        I’m a Staff Software Engineer currently working as Tech Lead of the Doc
        Squad at Algolia. I mostly do front-end development, and I’m a Vue.js
        and CSS nerd. I can &#x27;t shut up about test-driven development and
        utility-first CSS. I also share what I learn on my blog frontstuff.io,
        or at meetups and conferences.
      </p>
    </div>
  </div>
  <div class="grid">
    <div class="vsection">
      <div class="card" />
    </div>
    <div class="hsection">
      <div class="card" />
      <div class="card" />
    </div>
  </div>
</div>
