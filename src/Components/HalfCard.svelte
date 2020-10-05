<script>
    export let data = { name: 'Name', description: 'A simple description' }
</script>

<style>
    .card {
        background-color: #212121;
        border-radius: 8px;
        padding: 24px;
        transition: all 250ms ease-out;
    }
    .card:hover {
        background-color: #3a3a3a;
        transform: scale(1.1, 1.1);
        transition: all 300ms ease-out;
    }
    h3 {
        margin: 0px;
        font-size: 18px;
        font-weight: 600;
    }
    p {
        margin: 0px;
        margin-top: 4px;
        font-size: 14px;
        font-weight: 400;
    }
</style>

<div class="card">
    <h3>{data.name}</h3>
    <p>{data.description}</p>
</div>
