<script>
	import Nav from './nav.svelte';
</script>

<header>
	<h1>Dog Class</h1>
	<Nav />
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		align-items: baseline;
		padding: 1rem 1rem 2rem;
		color: var(--clr-pale-green);
		border-bottom: 2px solid var(--clr-pale-green);
		outline: 1px solid var(--clr-white);
	}
</style>
