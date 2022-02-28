<!-- @format !-->
<script lang="ts">
</script>

<svelte:head />

<div class="container">
	<div class="text">
		<h1>About</h1>
		Je kijkt naar de pagina van Thuiswork. Hevig WIP, nog lang niet af. Het is een plan om een open-source
		platform te maken om antwoorden op huiswerkopgaven te delen.

		<h3>Technologieën frontend:</h3>

		<ul>
			<li>SvelteKit</li>
			<li>Svelte</li>
			<li>URQL</li>
			<li>TypeScript</li>
		</ul>

		<h3>Technologieën backend:</h3>
		<ul>
			<li>NestJS</li>
			<li>TypeScript</li>
			<li>knex.js & PostGresQL</li>
			<li>GraphQL</li>
		</ul>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
	* {
		font-family: 'Montserrat', sans-serif;
	}
	.container {
		display: flex;
		text-align: left;
		flex-direction: column;
		align-items: center;
		height: 100vh;
	}
	.text {
		width: 60%;
	}
</style>
