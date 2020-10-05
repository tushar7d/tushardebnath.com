<script>
    import Card from './Card.svelte'
    import HalfCard from './HalfCard.svelte'
</script>

<style>
    .vsection {
        display: grid;
        grid-template-columns: 1fr;
        grid-row-gap: 15px;
        padding: 80px;
    }

    h1 {
        font-size: 32px;
        font-weight: 600;
        margin-bottom: 24px;
    }
    .col_2 {
        display: grid;
        grid-template-columns: 1fr 1fr;
        row-gap: 12px;
        column-gap: 12px;
    }
    @media only screen and (max-width: 991px) {
        h1 {
        font-size: 24px;
        font-weight: 600;
        margin-bottom: 24px;
    }
        .vsection {
        
        padding: 40px;
    }
  }
   
</style>

<div class="vsection">
    <h1>Projects</h1>
    <Card  data={{name: "Tushar", description: "An amazing component"}} />
    
    <h1>Writing</h1>
    <div class="col_2">
        <HalfCard />
        <HalfCard />
        
    </div>
</div>
