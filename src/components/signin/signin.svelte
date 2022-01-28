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
		<div>Don't have an account? <button class="signup">Sign up</button></div>
		<input type="submit" value="Login" />
	</form>
</div>
