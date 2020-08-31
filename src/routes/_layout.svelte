<script>
	// import Nav from "../components/Nav.svelte";
	import Stylesheet from "../components/Stylesheet.svelte";

	export let segment;
</script>

<style>
	main {
		position: relative;
		margin: 0 auto;
		/* padding: var(--nav-h) var(--side-nav) 0 var(--side-nav); */
		padding: var(--nav-h) 0 0 0;
		overflow-x: hidden;
	}
</style>

<Stylesheet />

<!-- <Nav {segment} /> -->

<main>
	<slot />
</main>
