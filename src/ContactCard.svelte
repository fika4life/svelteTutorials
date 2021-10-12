<script>
    export let userName;
    export let jobTitle;
    export let description;
    export let imgUrl;

</script>

<style>
    .card{
        border: 1px solid #eee;
        padding: 1em;
        margin: 1em;
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
        border-radius: 6px;
    }
    .thumb{
    }

    .thumb img {
        width: 200px;
        border-radius: 3px;
    }
    
</style>

<div class='card'>
    <header>
        <div class="thumb">
            <img src="{imgUrl}" alt="">
        </div>
      <div class='user-data'>
            <h1>{userName}</h1>
            <h2>{jobTitle}</h2>
        </div>
    </header>
    <div>
        <p>{description}</p>
    </div>
</div>