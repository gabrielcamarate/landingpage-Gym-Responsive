<div class="section">
	<div class="directions">
		<div class="left">
			<div class="blur"></div>
			<h1 class="title">READY TO LEVEL UP YOUR BODY</h1>
			<a href="/">Leia Mais</a>
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
				been the industry's standard dummy text ever since the 1500s,
			</p>
		</div>

		<div class="right">
			<div class="radial-blur"></div>
			<h2>PROGRAM</h2>
			<div class="image">
				<img src="/gym-image-section-two.jpg" alt="imagem" />
			</div>
		</div>
	</div>
</div>

<!-- ====================== CSS ====================== -->

<style>
	/* ====================== POSICIONAMENTO ====================== */

	.radial-blur {
		position: absolute;
		width: 2634px;
		height: 1988px;

        margin-top: -570px;
        margin-left: -800px;

		/* top: 1500px;
		left: 200px; */

		background: radial-gradient(
			42.1% 42.1% at 50% 50%,
			rgba(255, 61, 0, 0.31) 0%,
			rgba(255, 61, 0, 0) 100%
		);

		opacity: 0.7;
		z-index: -1;
	}

	.blur {
		position: absolute;
		width: 871px;
		height: 1080px;
		left: -179px;
		top: -130px;

		background: linear-gradient(187.76deg, #fd4c00 -14.26%, rgba(244, 117, 63, 0) 86.69%);
		transform: matrix(-1, 0, 0, 1, 0, 0);
		z-index: -1;
	}

	.section {
		display: flex;
		justify-content: center;
		margin-top: 80px;
	}

	.directions {
		display: flex;
		gap: 300px;
	}

	.left {
		display: flex;
		flex-direction: column;
		margin-left: 120px;
		margin-top: 130px;
		position: relative;
	}

	.right {
		display: flex;
		flex-direction: column;
		margin-top: 150px;
	}

	.right h2 {
		margin-bottom: 50px;
	}

	/* ====================== ESTILO DE TEXTOS ====================== */

	/*============== Left ==============*/
	.left h1 {
		width: 648px;
		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 900;
		font-size: 83px;

		color: var(--white);
	}

	.left a {
		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 700;

		margin: 50px 0 50px 0;
		text-align: center;

		color: var(--white);
		border: 3px solid var(--white);

		padding: 20px;
		width: 200px;
	}
	.left p {
		color: var(--white);
		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 700;

		max-width: 550px;
		font-size: 1.3em;
	}

	/* ============ Right ============*/

	.right h2 {
		color: var(--white);
		width: 648px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 53px;
	}

	.right img {
		width: 600px;
		border: var(--vermilion-600) solid 4px;
	}

	/*==================================*/
</style>