<!-- @format !-->
<script lang="ts">
	import Dummy from './dummy.svelte';
</script>

<div class="articlebox">
	<div class="article">
		<Dummy />
	</div>
</div>

<style>
	.articlebox {
		display: flex;
		justify-content: center;
		border-color: #333;
		width: auto;
		min-height: 700px;
		height: auto;
		padding-bottom: 50px;
	}
	.article {
		width: 60%;
		min-height: 350px;
		height: auto;
		border-color: #333;
		border-style: solid;
		padding: 15px;
	}
</style>
