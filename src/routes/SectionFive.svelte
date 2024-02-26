<script>
	let cards = [
		{
			img: '/gym-image-section-five-one.png',
			title: 'Crish Wokes',
			subtitle: 'Body Builder',
			description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
		},
		{
			img: '/gym-image-section-five-one.png',
			title: 'Crish Wokes',
			subtitle: 'Body Builder',
			description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
		},
		{
			img: '/gym-image-section-five-one.png',
			title: 'Crish Wokes',
			subtitle: 'Body Builder',
			description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
		},
		{
			img: '/gym-image-section-five-one.png',
			title: 'Crish Wokes',
			subtitle: 'Body Builder',
			description: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.'
		}
	];
</script>

<div class="section">
	<div class="title">
		<h1>MEMBER US</h1>
	</div>

	<div class="colluns">
		<div class="row-one">
			{#each cards as cd}
				<div class="item">
					<img src={cd.img} alt="" />
					<h1>{cd.title}</h1>
					<h2>{cd.subtitle}</h2>
					<p>{cd.description}</p>
				</div>
			{/each}
		</div>
		<div class="row-two">
			{#each cards as cd}
				<div class="item-two">
					<img src={cd.img} alt="" />
					<h1>{cd.title}</h1>
					<h2>{cd.subtitle}</h2>
					<p>{cd.description}</p>
				</div>
			{/each}
			<div class="degrade"></div>
		</div>
	</div>
</div>

<!-- ================== CSS ================== -->

<style>
	.section {
		margin-top: 170px;
	}

	.title {
		display: flex;
		justify-content: center;
	}

	.title h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 39px;
	}

	.colluns {
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.row-one {
		display: flex;
		margin-bottom: 60px;
		gap: 180px;
		justify-content: center;
	}

	.row-two {
		display: flex;
		justify-content: center;
		gap: 180px;
	}

	.item {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		text-align: center;
		margin-top: 60px;
	}

	.item img {
		max-width: 200px;
		border: 3px solid var(--vermilion-600);
		border-radius: 100%;
		margin-bottom: 30px;
	}

	.item h1 {
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 700;
		font-size: 22px;
		color: #fd4c00;
	}

	.item h2 {
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 15px;
	}

	.item p {
		width: 211px;
		margin-top: 20px;
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 11px;
	}

	.item-two {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		text-align: center;
		margin-top: 60px;
	}

	.item-two img {
		max-width: 200px;
		border: 4px solid var(--white);
		border-radius: 100%;
		margin-bottom: 30px;
	}

	.item-two h1 {
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 700;
		font-size: 22px;
	}

	.item-two h2 {
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 15px;
	}

	.item-two p {
		width: 211px;
		margin-top: 20px;
		font-family: 'Poppins', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 11px;
	}

	.degrade {
		position: absolute;
		width: 1921px;
		height: 476px;

		margin-left: 0px;
		margin-bottom: -530px;

		background: linear-gradient(83.99deg, #fe4c00 8.77%, rgba(244, 117, 63, 0) 90.03%);
		transform: matrix(1, 0, 0, -1, 0, 0);
		z-index: -1;
	}
</style>
