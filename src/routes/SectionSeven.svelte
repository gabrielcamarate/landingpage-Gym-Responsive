<div class="section">
	<div class="title">
		<h1>PERSONAL TRAINER</h1>
	</div>

	<div class="positions">
		<div class="left">
			<div class="box">
				<h1>Strength Training Power Lifter</h1>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
				<a href="/">Learn More</a>
			</div>

			<div class="box">
				<h1>Healthy Food Education Body</h1>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
				<a href="/">Learn More</a>
			</div>
		</div>

		<div class="right">
			<div class="box">
				<h1>Education for a Strong Life</h1>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
				<a href="/">Learn More</a>
			</div>

			<div class="box">
				<h1>Healthy Drink Education</h1>
				<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
				<a href="/">Learn More</a>
			</div>
		</div>
	</div>

	<div class="paragraph">
		<p>
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
			been the industry's standard dummy text ever since the 1500s.
		</p>
	</div>
</div>

<!-- ===================== CSS ===================== -->

<style>
	.paragraph {
		display: flex;
		justify-content: center;
		margin-top: 40px;
		margin-bottom: 100px;
	}

	.paragraph p {
		width: 1042px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 26px;
		text-align: center;
	}

	.section {
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.title {
		display: flex;
		justify-content: center;
		margin-bottom: 80px;
	}

	.positions {
		display: flex;
		justify-content: center;
		gap: 45px;
	}

	.box {
		display: flex;
		flex-direction: column;
		padding: 39px 40px;
		gap: 13px;

		width: 488px;
		height: 279px;

		background: rgba(46, 54, 60, 0.5);
		border: 0.907618px solid rgba(255, 255, 255, 0.2);
		backdrop-filter: blur(11.7083px);

		margin-bottom: 35px;
	}

	.box h1 {
		width: 244px;
		height: 66px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 800;
		font-size: 27.47px;
	}

	.box p {
		width: 408px;
		height: 60px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 17.0566px;
		color: #c9c9c9;
	}

	.box a {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 13px;

		text-align: center;
		max-width: 140px;
		background: var(--vermilion-600);
		padding: 10px 20px;
		transition: 0.2s;
	}

	.box a:hover {
		scale: 1.09;
	}
</style>
