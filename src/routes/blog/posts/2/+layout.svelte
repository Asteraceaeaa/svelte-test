<div class="container">
    <a href="/blog">Back to blogposts</a>
    <slot />
</div>

<style>
    .container {
        margin: 50px auto;
        max-width: 800px;
        padding: 0 20px;
    }

    .container a {
        text-decoration: underline;
        text-decoration-style: solid;
    }
</style>