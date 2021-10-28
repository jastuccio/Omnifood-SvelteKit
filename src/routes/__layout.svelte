<slot />

<!-- https://github.com/jonasschmedtmann/html-css-course/blob/master/starter/04-CSS-Layouts/style.css -->

<!-- https://github.com/jonasschmedtmann/html-css-course/blob/master/starter/08-Omnifood-Responsive/css/general.css -->
<style>
	:global(:root) {
		--gray: #555;
		--teal: #1098ad;
		/* color: red; */
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
</style>
