<script>
	window.onload = function() { document.body.classList.remove('is-preload'); }
	window.ontouchmove = function() { return false; }
	window.onorientationchange = function() { document.body.scrollTop = 0; }
</script>

<main>
	<h1>Wbsite of games in JavaScript!</h1>
	<div>
		<p>You want to play games:
			<br>
			<a href="snake.html">Snake.</a>
			<a href="tetris.html">Thetris.</a>
			<a href="dobblejump.html">Doble Jump.</a>
		</p>
	</div>
	<footer id="footer">
		<span class="copyright">&copy; Design: <a href="http://github.com/gleizits">Gleizits</a>.</span>
	</footer>
</main>

<style>
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
</style>