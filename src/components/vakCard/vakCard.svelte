<!-- @format !-->
<script lang="ts">
	export let plaatje: string;
	export let alt: string;
	export let tekst: string;
</script>

<div class="vak">
	<img src={plaatje} {alt} class="plaatje" />
	<div class="vaktekst">{tekst}</div>
</div>

<style>
	.vak {
		border-style: solid;
		height: 300px;
		width: 300px;
		border-color: #2a2b32;
		display: flex;
		border-radius: 10px;
		align-items: center;
		flex-direction: column;
		overflow: hidden;
		cursor: pointer;
		background-color: #2a2b32;
		color: #edf0f1;
		filter: grayscale(0%);
		transition: all 0.5s ease;
	}
	.vak:hover {
		border-width: 15px;
		background-color: #2a2b32;
		border-color: #2a2b32;
	}
	.plaatje {
		transition: all 0.5s ease;
	}
	.vak:hover > .plaatje {
		filter: grayscale(100%);
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
</style>
