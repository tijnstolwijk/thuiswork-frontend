<!-- @format !-->
<script>
</script>

<header>
	<!-- Logo!-->

	<img src="/logo.svg" />

	<!-- ^ Logo!-->

	<!-- Links !-->
	<nav>
		<ul class="links">
			<li><a href="#">Home</a></li>
			<li><a href="#">Vakken</a></li>
			<li><a href="#">About</a></li>
		</ul>
	</nav>

	<!-- Login button !-->
	<a class="cta" href="#"><button> login</button></a>
</header>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
	li,
	a,
	button {
		font-family: 'Montserrat', sans-serif;
		font-weight: 500;
		font-size: 16px;
		color: #edf0f1;
		text-decoration: none;
	}
	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 15px 10%;
		background-color: #24252a;
	}

	.links {
		list-style: none;
	}

	.links li {
		display: inline-block;
		padding: 0px 20px;
	}

	.links li a {
		transition: all 0.3s ease 0s;
	}

	.links li a:hover {
		color: #0088a9;
	}

	button {
		padding: 9px 25px;
		background-color: rgba(0, 136, 169, 1);
		border: none;
		border-radius: 50px;
		cursor: pointer;
		transition: all 0.3s ease 0s;
	}

	button:hover {
		background-color: rgba(0, 136, 169, 0.8);
	}
</style>
