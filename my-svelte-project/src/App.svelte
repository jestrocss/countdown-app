<script>
</script>

<svelte:head>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css"
	/>
</svelte:head>

<main>
	<div>a</div>
	<div>a</div>
	<div>a</div>
	<div>a</div>
</main>

<style>
	:global(html, body) {
		min-height: 100vh;
		overflow: hidden;
	}

	main {
		background-image: linear-gradient(90deg, #000, #333);
		min-height: 100vh;
		color: #fafafa;
		font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
			Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		gap: 100px;
	}
</style>
