<nav class="tv-static">
	<a href="/">home</a>
	<a href="/blog">blog</a>
	<a>socials</a>
</nav>

<slot />

<style>
	nav {
		text-align: center;
		/* make nav height equal to its inside contents */
		display: inline-flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}
	a {
		margin: 0 5px;
		box-shadow: 3px 3px 0 0 #00ffff;
		padding: 5px 10px;
		text-decoration: none;
		color: #00ffff;
		border: 1px solid #00ffff;
		transition: all 0.2s ease-in-out;
	}

	a:hover {
		box-shadow: none;
		font-weight: bold;
		background-color: #00ffff;
		color: #000000;
	}
</style>
