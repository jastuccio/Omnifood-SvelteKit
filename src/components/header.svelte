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
			<a href="#" class="btn btn--full margin-right-sm">Start eating well</a>
			<a href="#" class="btn btn--outline">Learn more &darr;</a>
			<div class="delivered-meals">
				<div class="delivered-imgs">
					<img src="img/customers/customer-1.jpg" alt="customer photo" />
					<img src="img/customers/customer-2.jpg" alt="customer photo" />
					<img src="img/customers/customer-3.jpg" alt="customer photo" />
					<img src="img/customers/customer-4.jpg" alt="customer photo" />
					<img src="img/customers/customer-5.jpg" alt="customer photo" />
					<img src="img/customers/customer-6.jpg" alt="customer photo" />
				</div>
				<p><span>250,000+</span> meals delivered last year!</p>
			</div>
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
	section {
		background-color: var(--headerBackground);
		padding: 9.6rem 0;
	}
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
		gap: 9.6rem;
		align-items: center;
	}

	img {
		width: 100%;
	}

	h1 {
		color: var(--darkGray);
		font-size: 5.2rem;
		font-weight: 700;
		line-height: 1.05;
		letter-spacing: -0.5px;
		margin-bottom: 3.2rem;
	}

	p {
		margin-bottom: 4.8rem;
	}

	.btn:link,
	.btn:visited {
		display: inline-block;
		color: var(--white);
		text-decoration: none;
		font-size: 2rem;
		font-weight: 600;
		padding: 1.6rem 3.2rem;
		border-radius: 9px;

		/* Put transition on original "state" */
		transition: background-color 0.3s;
	}

	.btn--full:link,
	.btn--full:visited {
		background-color: var(--primary);
		color: var(--white);
	}

	.btn--full:hover,
	.btn--full:active {
		background-color: var(--darkOrange);
	}

	.btn--outline:link,
	.btn--outline:visited {
		background-color: var(--white);
		color: var(--gray);
	}

	.btn--outline:hover,
	.btn--outline:active {
		background-color: var(--lighterOrange);

		/* border:  3px solid #fff; */
		/* ⬇️ CSS Trick to add border inside button and prevent page jump ⬇️ */
		box-shadow: inset 0 0 0 3px var(--white);
	}

	nav {
		font-size: 18px;
		/* text-align: center; */
	}

	nav a:link {
		/* background-color: orangered;
		margin: 20px;
		padding: 20px;
		display: block;
	*/

		margin-right: 30px;
		margin-top: 10px;
		display: inline-block;
	}

	nav a:link:last-child {
		margin-right: 0;
	}

	.delivered-meals {
		display: flex;
		align-items: center;
		gap: 1.6rem;
		margin-top: 8rem;
	}

	.delivered-meals p {
		font-size: 1.8rem;
		font-weight: 600;
		margin: 0;
	}

	.delivered-imgs {
		display: flex;
	}

	.delivered-imgs img {
		height: 4.8rem;
		width: 4.8rem;
		border-radius: 50%;
		margin-right: -1.6rem;
		border: 3px solid var(--lighterOrange);
	}
	.delivered-imgs img:last-child {
		margin: 0;
	}

	span {
		color: var(--darkOrange);
		font-weight: 700;
	}
</style>
