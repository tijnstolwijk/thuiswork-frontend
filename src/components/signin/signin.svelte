<!-- @format !-->
<svelte:head>
	<link src="/login.css" />
</svelte:head>
<div class="formcontainer">
	<form>
		<h1>Signin</h1>
		<div class="field">
			<input name="email" type="text" required />
			<span />
			<label> Email </label>
		</div>
		<div class="field">
			<input name="name" type="text" required />
			<span />
			<label> Username </label>
		</div>
		<div class="field">
			<input name="password" type="text" required />
			<span />
			<label> Password </label>
		</div>
		<input type="submit" value="Sign up" />
	</form>
</div>
