<script>
    export let data = { pub: 'Name', title: 'A simple description' }
</script>

<style>
    .card {
        background-color: #212121;
        border-radius: 8px;
        padding: 12px;
        transition: all 250ms ease-out;
    }
    .card:hover {
        background-color: #3a3a3a;
        transform: scale(1.1, 1.1);
        transition: all 300ms ease-out;
    }
    h3 {
        font-size: 14px;
        font-weight: 200;
        margin-bottom: 12px;
        opacity: 0.4;
       
    }
    p {
        margin: 0px;
        font-size: 16px;
        font-weight: 600;
    }
</style>

<div class="card">
    <h3>{data.pub}</h3>
    <p>{data.title}</p>
</div>
