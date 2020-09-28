<style>
    section {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding: 24px;
       height: calc(100% - 200px);
    }
    h1 {
        font-size: 44px;
        line-height: 1.2;
        font-weight: 600;
        margin: 0px;
        margin-bottom: 12px;
    }
    p {
        font-size: 14px;
        line-height: 1.5;
        margin: 0px;
    }
    .quick_link_container{

        display: flex;
        flex-direction: column;
        justify-content: flex-start;
    }
    .image_placeholder{
        width: 80px;
        height:80px;
        border-radius: 160px;
        background-color: white;

    }

    /* Extra small devices (phones, 600px and down) */
    @media only screen and (max-width: 600px) {
        section {
           
            padding: 24px;
        }

        p {
            font-size: 14px;
            line-height: 1.5;
            margin: 0px;
        }
    }

    /* Small devices (portrait tablets and large phones, 600px and up) */
    @media only screen and (min-width: 600px) {
        section {
          
            padding: 24px;
        }

        p {
            font-size: 14px;
            line-height: 1.5;
            margin: 0px;
        }
    }

    /* Medium devices (landscape tablets, 768px and up) */
    @media only screen and (min-width: 768px) {
        section {
            
            padding: 48px;
        }
        h1 {
            font-size: 44px;
            line-height: 1.2;
            margin: 0px;
            margin-bottom: 12px;
        }
        p {
            font-size: 14px;
            line-height: 1.5;
            margin: 0px;
        }
    }

    /* Large devices (laptops/desktops, 992px and up) */
    @media only screen and (min-width: 992px) {
        section {
         
            padding: 48px;
            padding-top: 80px;
        }
        h1 {
            font-size: 52px;
            line-height: 1.2;
            margin: 0px;
            margin-bottom: 12px;
        }
        p {
            font-size: 14px;
            line-height: 1.5;
            margin: 0px;
        }
    }

    /* Extra large devices (large laptops and desktops, 1200px and up) */
    @media only screen and (min-width: 1200px) {
        section {
            
            padding: 48px;
            padding-top: 80px;
        }
        h1 {
            font-size: 52px;
            line-height: 1.2;
            margin: 0px;
            margin-bottom: 12px;
        }
        p {
            font-size: 14px;
            line-height: 1.5;
            margin: 0px;
        }
    }
</style>

<section>
    <div>
        <h1>Hello, I’m Tushar Debnath</h1>
        <p class="paragraph">
            I am Tushar Debnath a Product designer & Design technologist living
            in New Delhi. Currently I am building consumer products and internal
            design tools at Zomato.
        </p>
    </div>
    <div class="quick_link_container">
        <div class="image_placeholder"></div>
    </div>
</section>
