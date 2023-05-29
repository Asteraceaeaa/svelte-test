<svelte:head>
    <title>Ковин Владимир</title> 
</svelte:head>

<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="info-text">
                    <h1>
                        <p class="animate-text-1">Lorem ipsum</p>
                        <p class="text-2">Lorem ipsum dolor</p>
                    </h1>
                </div>
                <h2 class="subtitle">
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quasi at, autem fuga tempore eveniet voluptatem recusandae. Dicta error suscipit quis atque expedita architecto incidunt exercitationem, perferendis hic neque voluptates quam!
                </h2>
                <div style="color:black" class="scroll-button animate-scroll" tabindex="0">
                    <a href="/about">Click Here</a>
                    <div class="arrow"></div>
                </div>
            </div>   
        </div>
    </div>
</div>

<div class="background-div"></div>

<style> 
    .info {
        text-align: center;
        position: relative;
    }

    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }

    .container {
        max-width: 1400px;
        margin: 190px 0 0 2.5rem
    }

    .info h1 {
        font-size: 4rem;
        margin: 0;
    }

    .info h1 p {
        position: relative;
    }
</style>