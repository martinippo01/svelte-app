<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>
		This is just a svelte hello world. <br>
		This is <i>ippo</i> getting to know svelte.<br>
		To see more projects (some real ones that have a purpose) visit <a href="https://ippo.com.ar/#projects" target="_blank">my projects portfolio.</a>
	</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>