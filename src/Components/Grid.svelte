<script>
    import Card from './Card.svelte'
    import HalfCard from './HalfCard.svelte'

    let data = [
        { name: 'Crystal Gems', description: 'A modular order tracking system for foor deliveries.', company: 'Zomato' },
        { name: 'Finding the Right Car', description: 'Helping car renters find the rigth car', company: 'Expedia' },
        { name: 'Keeping users engaged', description: 'User Retention strategy for retaining and growing the userbase ', company: 'Hike Messenger' },
        { name: 'Cosmos design system', description: 'Order Tracking system', company: 'Zomato' }
       
    ]
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
    {#each data as d}
    <Card data={{ name:d.name, description: d.description, company: d.company }} />
    {/each}
    <h1>Writing</h1>
    <div class="col_2">
        <HalfCard />
        <HalfCard />
    </div>
</div>
