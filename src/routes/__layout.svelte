<slot />

<!-- https://github.com/jonasschmedtmann/html-css-course/blob/master/starter/04-CSS-Layouts/style.css -->

<!-- https://github.com/jonasschmedtmann/html-css-course/blob/master/starter/08-Omnifood-Responsive/css/general.css -->
<style>
	:global(:root) {
		/* Define Colors as Colors */
		--white: #fff;
		--darkGray: #333;
		--gray: #555;
		--teal: #1098ad;
		--orange: #e67e22;
		--darkOrange: #cf711f;
		--lighterOrange: #fdf2e9;

		/* Define Colors as Intentions */
		--primary: var(--orange);
		--headerBackground: var(--lighterOrange);
	}

	/* Helper classes */
	:global(.margin-right-sm) {
		margin-right: 1.6rem !important;
	}

	:global(*) {
		/* border-top: 10px solid #1098ad; */
		box-sizing: border-box;
		margin: 0;
		padding: 0;
	}

	:global(html) {
		/* font-size: 10px; */
		/* 10px / 16px = 0.625 = 62.5% */
		/* Percentage of user's browser font-size setting */
		font-size: 62.5%;
	}

	:global(*, *:before, *:after) {
		box-sizing: inherit;
	}

	:global(body) {
		font-family: sans-serif;
		line-height: 1;
		font-weight: 400;
		color: var(--gray);
		/* border-top: 10px solid var(--teal); */
		/* position: relative; */
	}

	/* :global(h1, h2, h3) {
		color: var(--teal);
	}

	:global(h1) {
		font-size: 2.6rem;
		text-transform: uppercase;
		font-style: italic;
	}

	:global(h1::first-letter) {
		font-style: normal;
		margin-right: 0.5rem;
	} */

	:global(p) {
		font-size: 2rem;
		line-height: 1.6;
	}
</style>
