<script>
	const name = "Rockhopper-Penguin";
</script>

<main>
	<h1>{ name }</h1>
	<div>
        <p>
          <a href="https://www.facebook.com/penguin.s.seto/" target="_blank">
            <i class="nes-icon facebook is-large"></i>
          </a>
        </p>
        <p>
          <a href="https://github.com/rockhopper-penguin" target="_blank">
            <i class="nes-icon github is-large"></i
          ></a>
        </p>
      </div>
</main>

<style>
	* {
		margin: 0;
		padding: 0;
	}

	main {
		text-align: center;
		width: 90%;
		margin: auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	div {
		width: 100%;
		margin: auto;
	}

	div > p {
		display: inline-block;
		padding: 10px;
	}

	@media (min-width: 640px) {
		main {

		}
	}
</style>