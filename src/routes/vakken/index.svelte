<!-- @format !-->
<script lang="ts">
	import Vakcard from '../../components/vakCard/vakCard.svelte';
</script>

<div class="container">
	<Vakcard plaatje="/cicero.jpg" alt="Latijn, het vak" tekst="latijn" />
	<Vakcard plaatje="/acropolis.jpg" alt="grieks" tekst="grieks" />
	<Vakcard plaatje="/geschiedenis.jpg" alt="geschiedenis" tekst="geschiedenis" />
	<Vakcard plaatje="/dna.jpg" alt="biologie" tekst="biologie" />
	<Vakcard plaatje="/boek.jpg" alt="nederlands" tekst="nederlands" />
	<Vakcard plaatje="/scheikunde.jpg" alt="scheikunde" tekst="scheikunde" />
	<Vakcard plaatje="/natuurkunde.jpg" alt="natuurkunde" tekst="natuurkunde" />
	<Vakcard plaatje="/frans.jpg" alt="frans" tekst="frans" />
	<Vakcard plaatje="/duits.jpg" alt="duits" tekst="duits" />
	<Vakcard plaatje="/maths.png" alt="wiskunde" tekst="wiskunde" />
	<Vakcard plaatje="/engels.jpg" alt="engels" tekst="engels" />
	<Vakcard plaatje="/economie.jpg" alt="economie" tekst="economie" />
	<Vakcard plaatje="/maatschappijleer.jpg" alt="maatschappijleer" tekst="maatschappijleer" />
	<Vakcard plaatje="/informatica.png" alt="informatica" tekst="informatica" />
	<Vakcard plaatje="/levensbeschouwing.jpg" alt="levensbeschouwing" tekst="levensbeschouwing" />
	<Vakcard plaatje="/spanish.jpg" alt="spanish" tekst="spanish" />
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
	* {
		font-family: 'Montserrat', sans-serif;
	}
	.vak {
		border-style: solid;
		height: 300px;
		width: 300px;
		border-color: #24252a;
		display: flex;
		border-radius: 10px;
		align-items: center;
		flex-direction: column;
		overflow: hidden;
		cursor: pointer;
		background-color: #24252a;
		color: #edf0f1;
	}
	.vaktekst {
		margin: auto;
		font-size: 20px;
	}
	.plaatje {
		width: 100%;
		height: 80%;
		object-fit: cover;
	}

	.container {
		display: grid;
		grid-gap: 1rem;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		width: 80%;
		justify-self: center;
		align-self: center;
		justify-items: center;
		margin-top: 100px;
		margin-bottom: 100px;
	}
</style>
