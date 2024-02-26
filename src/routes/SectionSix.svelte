<script>
	const cards = [
		{
			img: '/icons/check-orange.svg',
			name: 'HAVE A PERSONAL TRAINER'
		},
		{
			img: '/icons/check-orange.svg',
			name: 'Free Personal Trainer for New Members'
		},
		{
			img: '/icons/check-orange.svg',
			name: 'Free Supplements for Every New Member'
		},
		{
			img: '/icons/check-orange.svg',
			name: 'Open 24 Hours'
		}
	];
</script>

<div class="section">
	<div class="container">
		<div class="left">
			<div class="two-images">
				<img src="/gym-image-section-six-one.svg" alt="" />
				<img src="/gym-image-section-six-two.svg" alt="" />
			</div>
			<img src="/gym-image-section-six-three.svg" alt="" />
		</div>

		<div class="right">
			<div class="informations">
				<div class="title">
					<h1>WHY CHOOSE US?</h1>
				</div>

				<div class="descriptions">
					<ul>
						{#each cards as cd}
							<li class="item">
								<span class="icon">
									<img src={cd.img} alt="" />
									<p>{cd.name}</p>
								</span>
							</li>
						{/each}
					</ul>
				</div>
				<div class="blur"></div>
			</div>
		</div>
	</div>
</div>

<!-- ================== CSS ================== -->

<style>
	.blur {
		position: absolute;
		width: 1921px;
		height: 403px;

		margin-left: -1220px;
        margin-top: -132px;

		background: linear-gradient(268.97deg, #fe4c00 -13.12%, rgba(244, 117, 63, 0) 74.81%);
		transform: matrix(1, 0, 0, -1, 0, 0);
		z-index: -1;
	}

	.section {
		margin-top: 250px;
		margin-bottom: 300px;
	}

	.container {
		display: flex;
		justify-content: center;
		gap: 100px;
	}

	.left {
		display: flex;
	}

	.left img {
		max-width: 630px;
		margin-left: 20px;
		border: 2px solid var(--vermilion-600);
	}

	.left .two-images {
		display: flex;
		flex-direction: column;
		gap: 20px;
	}

	.two-images img {
		max-width: 305px;
	}

	.title {
		width: 644px;
		font-family: 'Inter';
		font-style: normal;
		font-weight: 900;
		font-size: 35px;
	}

	.right {
		display: flex;
		margin-top: 70px;
	}

	.icon {
		display: flex;
		align-items: center;
		margin-top: 30px;
	}

	.icon p {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 25px;
	}
</style>
