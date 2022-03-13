<script>
	const links = [
		{
			title: 'Home',
			path: '/'
		},
		{
			title: 'About',
			path: '/about'
		}
	];
</script>

<nav>
	{#each links as link}
		<a href={link.path}>{link.title}</a>
	{/each}
</nav>

<style>
	a {
		text-decoration: none;
		margin: 0 1rem;
	}
</style>
