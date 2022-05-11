<script>
    export let text = "texto por defecto"
    export let width = "100%"
</script>

<div class="container" style="--width: {width}">
    <p>{text}</p>
</div>

<style>
    p {
        font-size: 2rem;
        text-align: center;
        color: #f3f3f3;
    }

    .container {
        width: var(--width);
        background: rgba( 0, 0, 0, 0.25 );
        box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
        backdrop-filter: blur( 4px );
        -webkit-backdrop-filter: blur( 4px );
        border-radius: 10px;
        border: 1px solid rgba( 255, 255, 255, 0.18 );
        padding: 1rem;
    }
</style>