<svelte:head>
    <title>Блог</title>
</svelte:head>
<script>
    import {routes} from "./routes"
</script>
<div class="container">
    <h1>Мои статьи</h1>
    <div class="blogposts">
        {#each routes as page}
            <div class="post">
                <h2>{page.title}</h2>
                <p>{page.body}</p>
                <p class="readmore">
                    <a href={`/src/blog/posts/${page.id}`} class="link">
                        Читать далее
                    </a>
                </p>
            </div>
        {/each}
    </div>

</div>

<style>
    .container {
        margin: 50px auto;
        max-width: 800px;
        padding: 0 20px;
    }

    .blogposts {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 20px;
    }

    .post {
        margin: 10px 0;
        border: 1px solid #aaafff;
        border-radius: 8px;
        padding: 5px 10px;
        box-shadow: 0 0 10px #eee;

    }

    .link {
        color: rgb(10, 10, 139)
    }
</style>