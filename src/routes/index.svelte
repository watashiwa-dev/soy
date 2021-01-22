<script>
	import successkid from 'images/pearrot.jpg';
</script>

<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 1.0em;
		text-transform: none;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
		font-size: 1.5em;
		font-style: italic;

	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Domains</title>
</svelte:head>

<h1>"Pearrot"</h1>

<figure>
	<img alt="Success Kid" src="{successkid}">
	<figcaption>Portrait d'un perroquet</figcaption>
</figure>

<p><strong>by Pam Sheehan</strong></p>
