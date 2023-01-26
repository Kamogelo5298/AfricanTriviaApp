<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/africa-logo.svg';
	import github from '$lib/images/africa-logo.svg';
</script>

<header>
	<div class="corner">
		<a href="https://kit.svelte.dev">
			<img src={logo} alt="SvelteKit" />
		</a>
	</div>

	<nav>
		<ul>
			<li><a href="/">Home</a></li>
			<li><a href="/quiz">Quiz</a></li>
			<li><a href="/wordsearch">Word Search</a></li>
		</ul>
	</nav>

	<div class="corner">
		<a href="https://github.com/sveltejs/kit">
			<img src={github} alt="GitHub" />
		</a>
	</div>
</header>

<style>
	nav {
  background-color: #333;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
  display: block;
}
nav ul li a:hover {
  background-color: #444;
}
</style>
