<div class="footer">
	<div class="container">
		<div class="left">
			<a href="/"><img src="/MAX-GYM.svg" alt="Logo da Academia" /></a>
			<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
				been the industry's standard dummy text ever since the 1500s.
			</p>
		</div>

		<div class="right">
			<div class="program">
				<h1>Program</h1>
				<ul>
					<li><a href="/" class="item">Strenght Training</a></li>
					<li><a href="/" class="item">Cardio Training</a></li>
					<li><a href="/" class="item">Helth Training</a></li>
					<li><a href="/" class="item">Shape Body</a></li>
				</ul>
			</div>

			<div class="program">
				<h1>About Us</h1>
				<ul>
					<li><a href="/" class="item">Strenght Training</a></li>
					<li><a href="/" class="item">Cardio Training</a></li>
					<li><a href="/" class="item">Helth Training</a></li>
					<li><a href="/" class="item">Shape Body</a></li>
				</ul>
				<div class="rectangle"></div>
			</div>
		</div>
	</div>
</div>

<!-- ============ CSS ============ -->

<style>
	.left img {
		transition: 0.2s;
	}

	.left img:hover {
		scale: 1.09;
	}

	.rectangle {
		position: absolute;
		width: 1920px;
		height: 526px;

		margin-left: -1500px;
		margin-top: -430px;

		background: #262e33;
		z-index: -1;
	}

	.footer {
		display: flex;
		justify-content: center;
	}

	.container {
		display: flex;
		margin-top: 150px;
		justify-content: center;
		gap: 400px;
	}

	.item {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 14px;
		transition: 0.2s;
	}

	.item:hover {
		color: var(--vermilion-600);
	}

	.right {
		display: flex;
		gap: 100px;
	}

	.program h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 24px;
	}

	.program {
		line-height: 45px;
	}

	.left p {
		width: 648px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 21px;
		line-height: 42px;
		text-align: justify;

		margin-top: 30px;
	}
</style>
