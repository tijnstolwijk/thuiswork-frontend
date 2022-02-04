<!-- @format !-->
<svelte:head>
	<link src="/login.css" />
</svelte:head>
<div class="formcontainer">
	<form>
		<h1>Login</h1>
		<div class="field">
			<input name="name" type="text" required />
			<span />
			<label> Username</label>
		</div>
		<div class="field">
			<input name="password" type="text" required />
			<span />
			<label> Password </label>
		</div>
		<div>Don't have an account? <a href="/signin"><button class="signup">Sign up</button></a></div>
		<input type="submit" value="Login" />
	</form>
</div>
