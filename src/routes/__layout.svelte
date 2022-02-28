<!-- @format !-->
<script lang="typescript">
	import Nav from '../components/layout/nav.svelte';
	import Footer from '../components/layout/footer.svelte';
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
		background-color: #24252a;
		color: #edf0f1;
	}
</style>
