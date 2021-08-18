<style>
	h1, h2, figure, p {
		text-align: center;
		margin: 0 auto;
    font-family: 'Open Sans'
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
  @font-face {
        font-family: 'Open Sans';
        font-style: normal;
        font-weight: 400;
        src: local('Open Sans'), local('OpenSans'), url(https://fonts.gstatic.com/s/opensans/v13/cJZKeOuBrn4kERxqtaUH3T8E0i7KZn-EPnyo3HZu7kw.woff) format('woff');
    }
</style>

<svelte:head>
	<title>Boilerplate Sapper</title>
</svelte:head>

<h1>Kasna Devs United</h1>
<h2>Boilerplate Frontend - Sapper</h2>

<figure>
	<img alt='Kasna' src='great-success.svg'>
	<figcaption></figcaption>
</figure>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>