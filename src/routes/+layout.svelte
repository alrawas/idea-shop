<script>
	import '$lib/assets/css/pico.min.css';
</script>

<div class="nav-wrapper">
	<nav class="container">
		<ul>
			<div class="logo-wrapper">
				<img class="logo" alt="logo" src="/images/logo_low_res.jpg" />
			</div>
      <span style="margin-left: 1rem;">IDEA Gift Shop</span>
		</ul>
		<ul>
			<li><a href="/">Home</a></li>
			<li><a href="/Shop">Shop</a></li>
			<li><a href="/about">About</a></li>
		</ul>
	</nav>
</div>

<div class="hero" />

<main class="container">
	<slot />
</main>

<div class="footer-wrapper">
	<footer class="container">hi</footer>
</div>

<style>
	.footer-wrapper {
		padding: 1rem;
		background-color: gray;
		color: whitesmoke;
	}
	.nav-wrapper {
		padding: 0.5rem 0.25rem;
		background-color: aliceblue;
	}
	main {
		padding: 2rem 1rem;
	}
	.hero {
		background-color: #394046;
		background-image: url('assets/sascha-eremin-DNQ-M93tHmA-unsplash-3000x1000.jpg');
		background-position: center;
		background-size: cover;
		height: 20vh;
	}
  .logo {
    height: 75px;
  }
</style>
