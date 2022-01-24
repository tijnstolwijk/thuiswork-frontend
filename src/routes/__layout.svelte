<!-- @format !-->
<script lang="typescript">
	import Nav from '../components/nav.svelte';
	import Footer from '../components/footer.svelte';
</script>

<body>
	<Nav />
	<slot />
	<Footer />
</body>

<style>
	* {
		margin: 0;
		padding: 0;
	}

	body {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}
</style>
