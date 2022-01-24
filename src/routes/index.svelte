<!-- @format
    Eerst standaard svelte layout maken
    script
    html
    css
!-->
<script lang="ts">
	import Articlebox from '../components/articlebox.svelte';
</script>

<svelte:head>
	<title>SvelteKit testing environment</title>
</svelte:head>
<body>
	<h1>Svelte test environment</h1>

	<Articlebox />
</body>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	h1 {
		color: #d08770;
	}
	body {
		display: flex;
		flex-direction: column;
	}
</style>
