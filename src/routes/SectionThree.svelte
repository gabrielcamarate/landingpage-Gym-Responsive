<div class="section">
	<div class="title"><h1>PERSONAL TRAINER</h1></div>

	<div class="items">
		<div class="left"><img src="/gym-image-section-three.svg" alt="Mulher malhando braço" /></div>

		<div class="middle">
			<!-- svelte-ignore a11y-img-redundant-alt -->
			<img src="/gym-image-section-three-two.jpg" alt="image" />

			<div class="rectangle">
				<h1>Treino de Força</h1>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
			</div>
		</div>

		<div class="right">
			<h1>ABOUT US</h1>
			<a href="/" class="button">Leia Mais</a>
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
				been the industry's standard dummy text ever since the 1500s,
			</p>
		</div>
	</div>
</div>

<!-- ==================== CSS ==================== -->

<style>
	/* =============== POSIÇÕES GLOBAIS =========== */
	.section {
		position: relative;
		display: flex;
		flex-direction: column;
		margin-top: 500px;
	}

	.section .title {
		display: flex;
		justify-content: center;
		margin-bottom: 80px;
	}

	.items {
		display: flex;
		justify-content: center;
		gap: 100px;
	}

	/* =========== LADO ESQUERDO =========== */
	.left img {
		position: absolute;
		max-width: 550px;
		margin-left: -50px;
		border: 4px solid var(--vermilion-600);
	}

	.title h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 53px;
		color: var(--white);
	}

    .left {
        transition: 0.2s;
    }

	.left:hover {
		scale: 1.09;
	}
    

	/* =========== MEIO =========== */

	.middle {
		display: flex;
		flex-direction: column;
		margin-left: 520px;
        transition: 0.2s;
	}

    .middle:hover {
        scale: 1.09;
    }

	.middle img {
		max-width: 433px;
	}

	.rectangle {
		width: 433px;
		height: 261.45px;
		background: linear-gradient(180deg, #fd4c00 0%, #f4753f 100%);
		border-radius: 0px;

		display: flex;
		flex-direction: column;

		text-align: center;
		align-items: center;
		justify-content: center;
	}

	.rectangle h1,
	.rectangle p {
		color: var(--white);
	}

	.rectangle h1 {
		font-family: 'Poppins';
		font-style: normal;
		font-weight: 800;
		font-size: 32.0358px;
		margin-bottom: 20px;
	}

	.rectangle p {
		max-width: 399.99px;
		width: 339.99px;
		font-family: 'Poppins';
		font-style: normal;
		font-weight: 400;
		font-size: 20px;
	}

	/* ====================== LADO DIREITO ====================== */

	.right h1 {
		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 900;
		font-size: 83px;
		color: var(--white);
	}

	.right a {
		font-family: 'Montserrat';
		font-style: normal;
		font-weight: 700;

		color: var(--white);
		border: 3px solid var(--vermilion-600);

		padding: 20px;
		max-width: 259px;
		text-align: center;
        transition: 0.2s;
	}

    .right a:hover {
        background: var(--vermilion-600);
        scale: 1.05;
    }

	.right {
		display: flex;
		flex-direction: column;
		gap: 30px;
		margin-top: 100px;
	}

	.right p {
		width: 517px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 26px;
		text-align: justify;
		color: #b3b3b3;
	}
</style>
