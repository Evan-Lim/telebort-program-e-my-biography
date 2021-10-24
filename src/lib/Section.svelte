<script>
export let title;
export let item1;
export let item2;
export let item3;
</script>

<div class="card card-custom">
    <h3 class="card-title">{title}</h3>
    <hr>
    <div class="card-body">
    <p>{item1}</p>
    <p>{item2}</p>
    <p>{item3}</p>
</div>
</div>



<style>
.card-custom{
    margin: 15px 300px;
}
</style>