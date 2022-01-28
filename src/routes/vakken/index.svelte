<!-- @format !-->
<script lang="ts">
</script>

<div class="container">
	<div class="vak">
		<img class="plaatje" src="/cicero.jpg" />
		<div class="vaktekst">/latijn</div>
	</div>

	<div class="vak">
		<img class="plaatje" src="/acropolis.jpg" />
		<div class="vaktekst">/grieks</div>
	</div>

	<div class="vak">
		<img class="plaatje" src="/geschiedenis.jpg" />
		<div class="vaktekst">/geschiedenis</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/dna.jpg" />
		<div class="vaktekst">/biologie</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/boek.jpg" />
		<div class="vaktekst">/nederlands</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/scheikunde.jpg" />
		<div class="vaktekst">/scheikunde</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/natuurkunde.jpg" />
		<div class="vaktekst">/natuurkunde</div>
	</div>
	<div class="vak">
		<img src="/frans.jpg" class="plaatje" />
		<div class="vaktekst">/frans</div>
	</div>
	<div class="vak">
		<img src="/duits.jpg" class="plaatje" />
		<div class="vaktekst">/duits</div>
	</div>
	<div class="vak">
		<img src="/maths.png" class="plaatje" />
		<div class="vaktekst">/wiskunde</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/engels.jpg" />
		<div class="vaktekst">/engels</div>
	</div>
	<div class="vak">
		<img class="plaatje" src="/economie.jpg" />
		<div class="vaktekst">/economie</div>
	</div>
	<div class="vak">
		<img src="/maatschappijleer.jpg" class="plaatje" />
		<div class="vaktekst">/maatschappijleer</div>
	</div>
	<div class="vak">
		<img src="/informatica.png" class="plaatje" />
		<div class="vaktekst">/informatica</div>
	</div>
	<div class="vak">
		<img src="/levensbeschouwing.jpg" class="plaatje" />
		<div class="vaktekst">/levensbeschouwing</div>
	</div>
	<div class="vak">
		<img src="/spanish.jpg" class="plaatje" />
		<div class="vaktekst">/spaans</div>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
	* {
		font-family: 'Montserrat', sans-serif;
	}
	.vak {
		width: 300px;
		height: 300px;
		border-style: solid;
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
		grid-gap: 15px;
		grid-template-columns: repeat(4, 1fr);
		width: 100%;
		justify-items: center;
		margin-top: 100px;
		margin-bottom: 100px;
	}
</style>
