<!-- @format
    Eerst standaard svelte layout maken
    script
    html
    css
!-->
<script lang="ts">
	import Dummy from '$lib/components/dummytxt/dummy.svelte';
</script>

<svelte:head>
	<title>Thuiswork CE</title>
</svelte:head>
<div class="container">
	<div class="text">
		<h2>Thuiswork CE: jouw open-source huiswerk-platform</h2>
		<h3>Thuiswork Community Edition</h3>
		<div class="field">
			<input name="name" type="text" required />
			<span />
			<label for="name">Zoeken op Thuiswork CE</label>
		</div>
		<Dummy />
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
	* {
		margin: 0;
		padding: 0;
		font-family: 'Montserrat', monospace;
	}
	h2 {
		margin: 5px;
		position: relative;
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
		color: #edf0f1;
		font-size: 18px;
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
		color: #edf0f1;
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
