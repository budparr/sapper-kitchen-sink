<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
	main {
		position: relative;
		max-width: 56em;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
		@apply bg-gray-300;
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>