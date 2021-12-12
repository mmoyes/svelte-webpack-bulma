<script>
	import Navbar from './navbar.svelte';
	export let name;
</script>

<main>
	<Navbar />
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<button class="button">Button</button> <button class="button is-dark">Dark</button>

	<section class="section">
		<h1 class="title">Section</h1>
		<h2 class="subtitle">This is a section y'all</h2>
		<p>blah blah blah</p>
	</section>


	<div class="columns">
		<div class="column">
			<textarea class="textarea is-dark" placeholder="Markdown Code"></textarea>
		</div>
		<div class="column">
			<div class="box">
				<h1>Section</h1>
				<h2>This is a section y'all</h2>
				<p>blah blah blah</p>				
			</div>
		</div>
	</div>

</main>

<!-- <style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style> -->

<style lang="text/scss">
@import "../node_modules/bulma/sass/utilities/_all.sass";
@import "./node_modules/bulma/sass/elements/button.sass";
@import "./node_modules/bulma/sass/elements/box.sass";
@import "./node_modules/bulma/sass/layout/section.sass";
@import "./node_modules/bulma/sass/grid/columns.sass";
@import "./node_modules/bulma/sass/form/_all.sass";
</style>