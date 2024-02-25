<nav class="main-navigation">
	<div class="container">
		<a href="/"><img src="/MAX-GYM.svg" alt="Logo da Academia" /></a>

		<ul class="navigation-links">
			<li><a href="/">Home</a></li>
			<li><a href="/">Product</a></li>
			<li><a href="/">Contact</a></li>
		</ul>

		<a href="/" class="button-navbar">Login</a>
	</div>
</nav>

<div class="hero-section">
	<div class="open-hours-square">
		<h2 class="open">OPEN <span class="hours">24H</span></h2>
	</div>

	<div class="left-content">
		<div class="blur-overlay"></div>

		<h1>FORMA SEU <span class="accent-color">CORPO</span></h1>

		<p>
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
			been the industry's standard dummy text ever since the 1500s.
		</p>

		<div class="call-to-actions">
			<a href="/" class="learn-more button-learn-more">Learn More</a>
			<a href="/" class="contact button-learn-more">Contact</a>
		</div>
	</div>

	<div class="right-content">
		<img src="/gym-image-header.jpg" alt="Mulher, malhando na academia." />
		<div class="gradient"></div>

		<div class="blur-overlay-two"></div>
	</div>
</div>

<!-- ======================== CSS ======================== -->
<style>
	/* ============= NAVBAR ============= */
	.button-navbar {
		font-size: 25px;
		padding: 15px 46px;
		border: 2px solid var(--white);
	}

	.container a {
		display: inline-block;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 600;
		color: var(--white);
		transition: 0.2s;

		/* margin-left: 450px; */
	}

	.container {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		/* justify-content: space-around; */
	}

	.main-navigation {
		padding: 30px 0px;
	}

	/* Aqui foi usado para mecher no home product contact */
	.container .button-navbar:hover {
		color: var(--white);
	}

	.container a:hover {
		display: inline-block;
		color: var(--vermilion-600);
		scale: 1.2;
	}

	.navigation-links {
		list-style-type: none;
		display: flex;
		margin: 0px 300px;
	}

	.navigation-links > li > a {
		font-size: 20px;
		margin: 30px 50px;
	}

	/* ========================================= */

	.blur-overlay {
		position: absolute;
		width: 1920px;
		height: 1482px;
		margin: -950px 0px 0px -1050px;
		background: radial-gradient(
			42.1% 42.1% at 50% 50%,
			rgba(255, 61, 0, 0.31) 0%,
			rgba(255, 121, 3, 0) 100%
		);
		z-index: -1;
	}

	.blur-overlay-two {
		position: absolute;
		width: 1920px;
		height: 1482px;
		margin: -1100px 0px 0px -600px;
		background: radial-gradient(
			42.1% 42.1% at 50% 50%,
			rgba(255, 61, 0, 0.31) 0%,
			rgba(255, 121, 3, 0) 100%
		);
		opacity: 0.7;
		z-index: -1;
	}

	.gradient {
		position: absolute;
		width: 590px;
		height: 1080px;

		margin-top: -843px;
		margin-left: 359px;

		/* right: 0;
		top: -425px; */

		background: linear-gradient(195.58deg, #fd4c00 12.53%, rgba(244, 117, 63, 0) 88.64%);
		transform: matrix(-1, 0, 0, 1, 0, 0);
		z-index: -1;
	}

	.right-content img {
		max-width: 851px;
		max-height: 913px;
		border: solid 3px var(--vermilion-600);
	}

	/* ============== BOTÕES ============== */

	.call-to-actions {
		display: flex;
		margin-top: 65px;
		gap: 2rem;
	}

	.learn-more {
		background-color: var(--vermilion-600);
		transition: 0.2s;
	}

	.learn-more:hover {
		display: flex;
		color: var(--white);
		scale: 0.9;

		background: transparent;
		border: 5px solid var(--vermilion-600);
	}
	.contact:hover {
		display: flex;
		background: var(--vermilion-600);
		border: none;
		scale: 0.9;
	}

	.contact {
		border: 5px solid var(--vermilion-600);
		transition: 0.2s;
	}

	.button-learn-more {
		display: flex;
		justify-content: center;
		align-items: center;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 600;
		font-size: 25px;
		color: var(--white);

		width: 259px;
		height: 93px;
	}

	.hero-section {
		display: flex;
		justify-content: center;
		position: relative;
		margin-top: 40px;
	}

	/* ============== QUADRADO ============== */
	.open-hours-square {
		position: absolute;

		width: 200px;
		height: 200px;

		margin-top: 300px;
		margin-left: 50px;

		display: flex;
		justify-content: center;
		align-items: center;
		background: var(--vermilion-600);
	}

	.open {
		max-width: 200px;
		color: var(--white);
		text-align: center;
		width: 136px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 900;
		font-size: 46.392px;
		line-height: 61px;

		text-align: center;
		color: var(--white);
	}

	.hours {
		width: 180px;
		height: 81px;
		left: 911px;
		top: 653.97px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 900;
		font-size: 62.7247px;
		/* identical to box height, or 129% */
		color: var(--white);
	}

	/* ============== LADO ESQUERDO ============== */

	.left-content {
		display: flex;
		flex-direction: column;
		margin-right: 95px;
		justify-content: center;
	}

	.left-content p {
		margin-top: 45px;
		max-width: 648px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 26px;
		line-height: 30px;
		color: var(--white);
	}

	.left-content h1 {
		max-width: 506px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 900;
		font-size: 83px;
		line-height: 107px;

		color: var(--white);
	}

	/* ============== COR ============== */

	.accent-color {
		color: var(--vermilion-600);
	}
</style>
