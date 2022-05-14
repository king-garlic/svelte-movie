<script>
	let count = 0;

	function incrementBtn() {
		// ++count;
		// count++;
		// count += 1;
		count += 2;
	}
</script>

<h1>Number : {count}</h1>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={incrementBtn}>increment</button>

<a href="/about">go to about</a>

<style>
	p {
		font-size: 2rem;
	}
</style>
