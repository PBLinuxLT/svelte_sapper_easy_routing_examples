<style>
	h1, figure, p, h4 {
		text-align: center;
		margin: 10px auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
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
	<title>Sapper project template With Easy Routing Starter!</title>
</svelte:head>

<h1>Great success!</h1>

<h4>To See Easy Routing in place, visit the src/routes/profile Folder and click the profile link!</h4>
<h4>Because life is complicated enough....</h4>
<p>For a more in depth use of Routing with server routes, please see the /src/routes/blog folder ;)</p>

<figure>
	<img alt='Success Kid' src='successkid.jpg'>
	<figcaption>Have fun with Sapper! Routing..</figcaption>
</figure>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>
