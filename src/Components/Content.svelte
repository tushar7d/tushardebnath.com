<style>
    section {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding: 80px;
       height: calc(100% - 120px);
    }
    h1 {
        font-size: 52px;
        line-height: 1.2;
        font-weight: 600;
        margin: 0px;
        margin-bottom: 28px;
    }
    p {
        font-size: 18px;
        line-height: 1.5;
        margin: 0px;
    }
    .quick_link_container{

        display: flex;
        
        align-items: center;
    }
    .image_placeholder{
        width: 60px;
        height:60px;
        border-radius: 160px;
        background-color: white;


    }
    .link{
        margin-left: 12px;
    }

    @media only screen and (max-width: 991px) {
        h1 {
        font-size: 32px;
        line-height: 1.2;
        font-weight: 600;
        margin: 0px;
        margin-bottom: 28px;
    }
    p {
        font-size: 18px;
        line-height: 1.5;
        margin: 0px;
    }
    .quick_link_container {
      display: none;
    }
    section {
        padding: 40px;
       height: auto;
    }
  }

</style>

<section>
    <div>
        <h1>Hello, I’m Tushar Debnath</h1>
        <p class="paragraph">
            A Product designer & Design technologist living
            in New Delhi. Currently I am building consumer products and internal
            design tools at Zomato.
        </p>
    </div>
    <div class="quick_link_container">
        <div class="image_placeholder" />
        <div class="link">LinkedIn</div>
        <div class="link">Figma</div>
        <div class="link">Dribbble</div>
        <div class="link">Github</div>

    </div>
</section>
