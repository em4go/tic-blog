<svelte:head>
	<link rel="stylesheet" href="/src/normalize.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
    href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&family=Roboto:wght@300;400;700&display=swap"
    rel="stylesheet">
</svelte:head>

<div class="root">
    <slot></slot>
</div>

<style>
    .root {
        width: 100vw;
        max-width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>