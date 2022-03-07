<!-- @format !-->
<script lang="ts">
	import Vakcard from '../../components/vakCard/vakCard.svelte';
</script>

<div class="container">
	<Vakcard plaatje="/cicero.jpg" alt="Latijn, het vak" tekst="latijn" link="vakken/latijn" />
	<Vakcard plaatje="/acropolis.jpg" alt="grieks" tekst="grieks" link="vakken/grieks" />
	<Vakcard
		plaatje="/geschiedenis.jpg"
		alt="geschiedenis"
		tekst="geschiedenis"
		link="vakken/geschiedenis"
	/>
	<Vakcard plaatje="/dna.jpg" alt="biologie" tekst="biologie" link="vakken/biologie" />
	<Vakcard plaatje="/boek.jpg" alt="nederlands" tekst="nederlands" link="vakken/nederlands" />
	<Vakcard plaatje="/scheikunde.jpg" alt="scheikunde" tekst="scheikunde" link="vakken/scheikunde" />
	<Vakcard
		plaatje="/natuurkunde.jpg"
		alt="natuurkunde"
		tekst="natuurkunde"
		link="vakken/natuurkunde"
	/>
	<Vakcard plaatje="/frans.jpg" alt="frans" tekst="frans" link="vakken/frans" />
	<Vakcard plaatje="/duits.jpg" alt="duits" tekst="duits" link="vakken/duits" />
	<Vakcard plaatje="/maths.png" alt="wiskunde" tekst="wiskunde" link="vakken/wiskunde" />
	<Vakcard plaatje="/engels.jpg" alt="engels" tekst="engels" link="vakken/engels" />
	<Vakcard plaatje="/economie.jpg" alt="economie" tekst="economie" link="vakken/economie" />
	<Vakcard
		plaatje="/maatschappijleer.jpg"
		alt="maatschappijleer"
		tekst="maatschappijleer"
		link="vakken/maatschappijleer"
	/>
	<Vakcard
		plaatje="/informatica.png"
		alt="informatica"
		tekst="informatica"
		link="vakken/informatica"
	/>
	<Vakcard
		plaatje="/levensbeschouwing.jpg"
		alt="levensbeschouwing"
		tekst="levensbeschouwing"
		link="vakken/levensbeschouwing"
	/>
	<Vakcard plaatje="/spanish.jpg" alt="spanish" tekst="spanish" link="vakken/spaans" />
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
