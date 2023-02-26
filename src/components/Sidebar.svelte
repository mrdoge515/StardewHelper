<script lang="ts">
</script>

<div class="Sidebar">
	<h1>StardewHelper</h1>

	<a href="/seasonGoals">Seasonal goals</a> <br />
	<a href="/communityBundles">Community bundles</a> <br />
	<a href="/calendar">Calendar</a>
</div>

<style>
	.Sidebar {
		min-width: 250px;
		background-color: #dce0e8; /* Latte Crust */
		color: #5c5f77; /* Latte Subtext1 */
		font-family: Arial, Helvetica, sans-serif;
		text-align: center;
	}

	h1 {
		padding: 1em 0;
		font-size: 1.5em;
	}

	a {
		color: #dc8a78; /* Latte Rosewater */
		transition: 0.5s ease-in;
		transition-property: color font-size;
		text-decoration: none;
		font-size: 1.4em;
		line-height: 1.4em;
	}
	a:hover {
		color: #d20f39; /* Latte Red */
		animation: linkAnim 1s;
		font-size: 1.6em;
	}

	/* Dark Mode */
	@media (prefers-color-scheme: dark) {
		.Sidebar {
			background-color: #181926; /* Macchiato Crust */
			color: #b8c0e0; /* Macchiato Crust */
		}

		a {
			color: #f4dbd6; /* Macchiato Rosewater */
		}
		a:hover {
			color: #ed8796; /* Macchiato Red */
		}
	}
</style>
