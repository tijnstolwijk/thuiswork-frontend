<!-- @format
    Eerst standaard svelte layout maken
    script
    html
    css
!-->
<script lang="ts">
	import Dummy from '../components/dummy.svelte';
</script>

<svelte:head>
	<title>SvelteKit testing environment</title>
</svelte:head>
<div class="container">
	<div class="text">
		<h1>==>Thuiswork CE: jouw gedecentraliseerde huiswerk-platform</h1>
		<h3>Thuiswork Community Edition</h3>
		<div class="field">
			<input name="name" type="text" required />
			<span />
			<label>Zoeken op Thuiswork CE</label>
		</div>
		<Dummy />
	</div>
</div>

<style>
	@import url(https://cdn.jsdelivr.net/npm/firacode@6.2.0/distr/fira_code.css);
	* {
		margin: 0;
		padding: 0;
		font-family: 'Fira Code', monospace;
	}
	h1 {
		color: #4c566a;
		margin: 5px;
	}
	.container {
		display: flex;
		text-align: left;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.text {
		width: 60%;
	}
	.field {
		position: relative;
		border-bottom: 2px solid #adadad;
		margin: 30px 0;
	}
	.field input {
		width: 100%;
		padding: 0 5px;
		height: 40px;
		font-size: 16px;
		border: none;
		background: none;
		outline: none;
	}
	.field label {
		position: absolute;
		top: 50%;
		left: 5px;
		color: #adadad;
		transform: translateY(-50%);
		font-size: 16px;
		pointer-events: none;
		transition: 0.5s;
	}
	.field span::before {
		content: '';
		position: absolute;
		top: 40px;
		left: 0;
		width: 0%;
		height: 2px;
		background: #2691d9;
		transition: 0.5s;
	}
	.field input:focus ~ label,
	.field input:valid ~ label {
		top: -5px;
		color: #2691d9;
	}
	.field input:focus ~ span::before,
	.field input:valid ~ span::before {
		width: 100%;
	}
</style>
