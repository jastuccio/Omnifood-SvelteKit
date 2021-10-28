<!-- section-hero -->
<section>
	<hero>
		<!-- hero-text-box -->
		<div>
			<!-- heading-primary -->
			<h1>A healthy meal delivered to your door, every single day</h1>

			<!-- hero description -->
			<p>
				The smart 365-days-per-year food subscription that will make you eat healthy again. Tailored
				to your personal tastes and nutritional needs.
			</p>
			<a href="#" class="btn">Start eating well</a>
			<a href="#" class="btn">Learn more &darr;</a>
		</div>

		<!-- hero-img-box -->
		<div>
			<!-- hero-img -->
			<img
				src="img/hero.png"
				alt="Woman enjoying food, meals in storage container, and food bowls"
			/>
		</div>
	</hero>
</section>

<style>
	hero {
		/***************************************************************************
		 * Using `width` would create horiziontal scrolling on smaller screen sizes
		 * max-width: 100% will fill the parent container.
		 * In this case it is the div that is 1 of 2 colums in our grid
		***************************************************************************/
		max-width: 130rem;
		margin: 0 auto; /* center the hero */
		display: grid;
		grid-template-columns: 1fr 1fr;
	}

	img {
		width: 100%;
	}

	nav {
		font-size: 18px;
		/* text-align: center; */
	}

	nav a:link {
		/* background-color: orangered;
  margin: 20px;
  padding: 20px;
  display: block; */

		margin-right: 30px;
		margin-top: 10px;
		display: inline-block;
	}

	nav a:link:last-child {
		margin-right: 0;
	}
</style>
