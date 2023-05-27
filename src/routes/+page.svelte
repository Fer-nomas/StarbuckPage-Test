<script>
	import Header from './componentes/Header.svelte';
	import Body from './componentes/Body.svelte';
</script>

<div class="container">
	<Header />
	<Body />
</div>

<style>
	:global(body) {
		margin: 0;
		overflow-x: hidden;
	}
	.container {
		height: 100vh;
		width: 100%;
		display: flex;
		flex-direction: column;
	}
</style>
