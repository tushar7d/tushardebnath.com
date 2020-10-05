<script>
    export let data = {name: "Name", description:"A simple description", company:"company"};

</script>
<style>
    .card {
        background-color: #212121;
        border-radius: 8px;
        padding: 24px;
        transition: all 250ms ease-out;
        opacity: 1;
    }
    .card:hover {
        background-color: #3a3a3a;
        transform: scale(1.1, 1.1);
        transition: all 300ms ease-out;
        opacity: 1;
    }
    
    h3 {
        margin: 0px;
        font-size: 18px;
        font-weight: 600;
       
    }
    p {
        margin: 0px;
        margin-top: 8px;
        font-size: 16px;
        font-weight: 400;
        opacity: 0.4;
    }
    .comp{
        font-size: 14px;
        font-weight: 200;
        margin-bottom: 12px;
        opacity: 0.4;

    }
</style>
<div class="card">
    <div class="comp">{data.company}</div>
    <h3>{data.name}</h3>
    <p>{data.description}</p>
   
</div>
