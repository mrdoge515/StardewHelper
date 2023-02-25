<script lang="ts">
	import '../main.css';
</script>

<main>
	<h1>StardewHelper</h1>
	<a href="https://mrdoge.xyz">Under construction</a>
</main>

<svelte:head>
	<title>StardewHelper</title>
</svelte:head>

<style>
	main {
		min-height: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;

		background-color: #eff1f5;
	}

	h1 {
		font-family: Arial, Helvetica, sans-serif;
		font-size: 3em;
		color: #4c4f69;
		transition: color 0.5s ease-in;
	}

	a {
		font-family: Arial, Helvetica, sans-serif;
		font-size: 2em;
		color: #4c4f69;
		transition: color 0.5s ease-in;
	}
	a:hover {
		color: #dc8a78;
	}

	@media (prefers-color-scheme: dark) {
		main {
			background-color: #24273a;
		}

		h1 {
			color: #cad3f5;
		}

		a {
			color: #cad3f5;
		}
		a:hover {
			color: #f4dbd6;
		}
	}
</style>
