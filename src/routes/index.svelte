<script context="module">
	export const prerender = true;
</script>
<script>
	import Navbar from '$lib/Navbar.svelte'
	import Header from '$lib/header/Header.svelte'
	import BlogEntry from '$lib/BlogEntry.svelte'
	import Footer from '$lib/Footer.svelte'
	import Quote from '$lib/quote/Quote.svelte'
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<Navbar />
<Header />

<main class="articles">
	<div class="blog-entry-container">
		<BlogEntry 
		title={"Canales de youtube para aprender desarrollo web"}
		date={"7 de mayo de 2022"}
		imgPath={"coffee.jpg"}
		imgAlt={"Ilustración 3D con objetos marrones"}
		link={"canales-youtube-desarrollo-web"}
		/>
	</div>
	<div class="blog-entry-container">
		<BlogEntry 
		title={"Segundo artículo del blog"}
		date={"12 de mayo de 2022"}
		imgPath={"purple.jpg"}
		imgAlt={"Ilustración 3D con objetos morados"}
		imageRight={true}
		/>
	</div>
	<div class="blog-entry-container">
		<BlogEntry 
		title={"Tercer artículo del blog"}
		date={"31 de mayo de 2022"}
		imgPath={"shapes.jpg"}
		imgAlt={"Ilustración 3D con objetos de distintos colores"}
		/>
	</div>
</main>

<Footer>
	<Quote />
</Footer>

<style global>

	main {
		width: 100%;
		margin-top: 4rem;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.blog-entry-container {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 95%;
	}
</style>
