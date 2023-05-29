<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Ковин Владимир</a>
        <div class="nav-links"></div>
        <a href="/about" class="link">Обо мне</a>
        <a href="/blog" class="link">Блог</a>
        <a href="/projects" class="link">Портфолио</a>
        <a href="/contact" class="link">Контакты</a>
    </div>
</nav>

<div class="container">
    <slot></slot>
</div>

<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }  
</style>