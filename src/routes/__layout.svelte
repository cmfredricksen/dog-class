<script>
	import '../../static/global.css';
	import Footer from '$lib/footer.svelte';
	import Header from '$lib/header.svelte';
</script>

<Header />
<div class="wrapper">
	<slot />
</div>
<Footer />

<style>
	.wrapper {
		width: 80%;
		margin: 1rem auto;
	}
</style>
