<div class="section">
	<h1 class="title-section">Programa</h1>

	<div class="boxes">
		<div class="boxs">
			<img class="icon" src="/icons/icon-SectionOne-one.svg" alt="Icone de um peso de academia" />
			<h1>Treinamento de força</h1>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>

			<div class="join-now">
				<a href="/">
					<h2>Entre Agora</h2>
					<img src="/icons/icon-arrow-right.svg" alt="Icone de uma seta para direita" />
				</a>
			</div>
		</div>

		<div class="boxs">
			<img class="icon" src="/icons/icon-SectionOne-two.png" alt="Icone de um peso de academia" />
			<h1>Treinamento cardíaco</h1>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>

			<div class="join-now">
				<a href="/">
					<h2>Entre Agora</h2>
					<img src="/icons/icon-arrow-right.svg" alt="Icone de uma seta para direita" />
				</a>
			</div>
		</div>

		<div class="boxs">
			<img class="icon" src="/icons/icon-SectionOne-three.svg" alt="Icone de um peso de academia" />
			<h1>Treinamento em Saúde</h1>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
			<div class="join-now">
				<a href="/">
					<h2>Entre Agora</h2>
					<img src="/icons/icon-arrow-right.svg" alt="Icone de uma seta para direita" />
				</a>
			</div>
		</div>

		<div class="boxs">
			<img class="icon" src="/icons/icon-SectionOne-four.svg" alt="Icone de um peso de academia" />
			<h1>Corpo em Forma</h1>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>

			<div class="join-now">
				<a href="/">
					<h2>Entre Agora</h2>
					<img src="/icons/icon-arrow-right.svg" alt="Icone de uma seta para direita" />
				</a>
			</div>
		</div>
	</div>

	<div class="footer-section">
		<p>
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
			been the industry's standard dummy text ever since the 1500s.
		</p>
	</div>
</div>

<!-- ================ CSS ================ -->

<style>
	.footer-section p {
        
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 1.3em;
		text-align: center;
		color: var(--white);
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}

	/* Inside auto layout */

	.footer-section {
		display: flex;
		justify-content: center;
		max-width: 1042px;
		
        margin: 0 auto;
        margin-top: 114px;
        margin-bottom: 40px;
	}

	.join-now {
		margin-top: 48px;
	}

	.join-now a {
		display: flex;
		max-height: 80px;
		justify-content: space-between;
		font-family: 'Poppins', sans-serif;
		font-weight: 600;
		color: #c9c9c9;
		padding: 5px 10px;
		transition: 0.2s;
	}

	.join-now a:hover {
		background: var(--vermilion-600);
		border-radius: 15px;
	}

	.icon {
		width: 57px;
	}

	.boxes {
		display: flex;
		justify-content: center;
		gap: 50px;
	}

	.boxs {
		display: flex;
		flex-direction: column;

		width: 290.82px;
		height: 316.19px;
		background: rgba(46, 54, 60, 0.5);
		border: 0.852832px solid rgba(255, 255, 255, 0.2);
		backdrop-filter: blur(11.0015px);

		padding: 20px;
		transition: 0.2s;
	}

	.boxs:hover {
		scale: 1.09;
	}

	.boxs h1 {
		font-family: 'Poppis', sans-serif;
		font-style: normal;
		font-weight: 800;
		font-size: 20px;
		color: var(--white);
		margin-top: 16px;
	}

	.boxs p {
		width: 226px;
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 17px;
		color: #c9c9c9;
		margin-top: 16px;
	}

	.title-section {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 53px;
		text-align: center;
		color: var(--white);

		margin-top: 300px;
		margin-bottom: 114px;
	}
</style>
