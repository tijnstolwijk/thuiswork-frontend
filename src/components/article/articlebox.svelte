<!-- @format !-->
<script lang="ts">
	import Dummy from '../dummytxt/dummy.svelte';
</script>

<div class="articlebox">
	<div class="articleheader">
		<img src="/geschiedenis.jpg" alt="profile picture" />

		<span>kaaskopVertaler in nederlands</span>
		<span>een opdracht ofzo</span>
		<div />
	</div>
	<div class="articlecontent">
		<Dummy />
	</div>
	<div class="articlefooter">
		<button>comments</button>
		<button class="regularbutton">share</button>
	</div>
</div>

<style>
	.vote {
		display: flex;
		flex-direction: column;
	}
	.articlebox {
		width: 60vw;
		background-color: #24252a;
		color: #edf0f1;
		display: flex;
		text-align: left;
		flex-direction: column;
		justify-content: center;
		border-radius: 1em;
		margin-bottom: 10px;
		margin-top: 10px;
	}
	.articlecontent {
		min-height: 500px;
		margin: 10px;
	}
	.articleheader {
		height: 7vh;
		margin: 10px;
		display: flex;
		justify-content: space-between;
		align-items: center;
		border-bottom: 1px solid silver;
	}

	.articlefooter {
		display: flex;
		margin: 10px;
		justify-content: space-between;
		align-items: center;
		height: 6vh;
		border-top: 1px solid silver;
	}
	button {
		padding: 9px 25px;
		border: none;
		border-radius: 50px;
		cursor: pointer;
		transition: all 0.3s ease 0s;
		font-family: 'Montserrat', sans-serif;
		font-weight: 500;
		font-size: 16px;
		color: #edf0f1;
		background-color: rgba(0, 136, 169, 1);
		text-decoration: none;
	}

	button:hover {
		background-color: rgba(0, 136, 169, 0.8);
	}
	img {
		border-radius: 50%;
		width: 50px;
		height: 50px;
		margin: 10px;
	}
</style>
