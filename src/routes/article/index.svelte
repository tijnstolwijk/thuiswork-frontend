<!-- @format !-->
<script lang="ts">
	import ArticleBox from '../../components/article/articlebox.svelte';
</script>

<div>
	<div class="field">
		<input name="name" type="text" required />
		<span />
		<label>Zoeken in nederlands</label>
	</div>
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
	<ArticleBox />
</div>

<style>
	div {
		display: flex;
		justify-content: center;
		flex-direction: column;
		align-items: center;
		margin: 5px;
	}
	.field {
		position: relative;
		border-bottom: 2px solid #adadad;
		margin: 30px 0;
		color: #edf0f1;
		width: 49vw;
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
		color: #edf0f1;
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
