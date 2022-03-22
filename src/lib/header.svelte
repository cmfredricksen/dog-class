<script>
	import Nav from './nav.svelte';
	import '../../static/global.css';
</script>

<header>
	<a href="/">
		<h1>Dog Class</h1>
	</a>
	<a href="/">
		<i class="material-icons-outlined"> pets </i>
	</a>
	<Nav />
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 1rem 1rem 2rem;
		color: var(--clr-pale-green);
		border-bottom: 2px solid var(--clr-pale-green);
		outline: 1px solid var(--clr-white);
	}

	header i {
		border: 2px solid var(--clr-pale-green);
		padding: 0.35rem;
		border-radius: 1.5rem;
		color: var(--clr-magenta);
	}

	header i:hover {
		/* border: 2px solid var(--clr-white); */
		color: var(--clr-white);
	}

	header h1:hover {
		color: var(--clr-white);
	}
</style>
