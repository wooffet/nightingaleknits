<script>
	import Header from '$lib/components/Header.svelte';
	import '$lib/styles/app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer>this is a footer</footer>
