<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
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