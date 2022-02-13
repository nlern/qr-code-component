<script context="module" lang="ts">
	import '../app.css';
	import Card from  '$lib/Card.svelte';
	export const prerender = true;
</script>

<svelte:head>
	<title>QR Code</title>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
	<link
		href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<section class="wrapper">
	<Card />
</section>

<style>
	.wrapper {
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin: 0 1.5rem;
	}

	@media screen and (min-width:375px) {
		.wrapper {
			width: 375px;
			margin: 0 auto;
		}
	}
</style>
