<script>
    export let bgImg = "";
    export let title = "";
</script>

<header style="--img: url({bgImg})">
    <h1>{title}</h1>
</header>

<style>
    header {
        box-sizing: border-box;
        background-color: #000;
        background-image: var(--img);
        background-size: cover;
        width: 100%;
        height: 90vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    h1 {
        font-family: 'Montserrat', sans-serif;
        color: #fff;
        text-align: center;
        font-size: 3.5rem;
        background-color: #000;
        width: 100%;
        padding-left: 1em;
        padding-right: 1em;
        padding-top: 0.5em;
        padding-bottom: 0.5em;
    }
</style>