<script lang="ts">
	let actuallyCard = 'card-2';

	function onEnter(event: any) {
		actuallyCard = event.target.id;
	}

	function onLeave(event: any) {
		actuallyCard = 'card-2';
	}
</script>

<div class="section">
	<div class="row row-top"></div>
	<div class="title">
		<h1>SIMPLE,TRANSPARENT PRICING</h1>
	</div>

	<div class="prices">
		<!-- svelte-ignore a11y-no-static-element-interactions -->
		<div
			class:currentCard={actuallyCard === 'card-1'}
			on:mouseenter={onEnter}
			on:mouseleave={onLeave}
			class="card"
			id="card-1"
		>
			<div class="title-name">
				<h2>BASIC PLAN</h2>
				<div class="row"></div>
				<div class="price-and-month">
					<h1>$12</h1>
					<h2>/Month</h2>
				</div>
				<p class="paragraph">
					Lorem Ipsum is simply dummy text of the printing and typesetting industry.
				</p>
				<div class="more-infos">
					<ul>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
					</ul>
				</div>
				<a href="/" class="button">Learn More</a>
			</div>
		</div>

		<!-- svelte-ignore a11y-no-static-element-interactions -->
		<div
			on:mouseenter={onEnter}
			on:mouseleave={onLeave}
			class="card-middle"
			class:currentCard={actuallyCard === 'card-2'}
			id="card-2"
		>
			<div class="title-name">
				<h2>PREMIUM PLAN</h2>
				<div class="row"></div>

				<div class="price-and-month-middle">
					<h1>$20</h1>
					<h2>/Month</h2>
				</div>

				<p class="paragraph-middle">
					Lorem Ipsum is simply dummy text of the printing and typesetting industry.
				</p>

				<div class="more-infos">
					<ul>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info-middle">
							<img src="/icons/check-white.png" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
					</ul>
				</div>
				<a href="/" class="button-middle">Learn More</a>
			</div>
		</div>

		<!-- svelte-ignore a11y-no-static-element-interactions -->
		<div
			class:currentCard={actuallyCard === 'card-3'}
			on:mouseenter={onEnter}
			on:mouseleave={onLeave}
			class="card"
			id="card-3"
		>
			<div class="title-name">
				<h2>PRO PLAN</h2>
				<div class="row"></div>

				<div class="price-and-month">
					<h1>$30</h1>
					<h2>/Month</h2>
				</div>

				<p class="paragraph">
					Lorem Ipsum is simply dummy text of the printing and typesetting industry.
				</p>

				<div class="more-infos">
					<ul>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
						<li class="info">
							<img src="/icons/check.svg" alt="Icone de Check" class="check" />
							<h3>All Service With Us</h3>
						</li>
					</ul>
				</div>
				<a href="/" class="button">Learn More</a>
			</div>
		</div>
	</div>
</div>

<!-- ============== CSS ============== -->

<style>
	.currentCard {
        transition: 0.2s;
		scale: 1.15;
	}

	.section {
		margin-top: 100px;
		margin-bottom: 100px;
	}

	.title {
		display: flex;
		justify-content: center;
		margin-bottom: 130px;
	}

	.title h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 47px;
	}

	.prices {
		display: flex;
		justify-content: center;
		gap: 50px;
	}

	.card {
		max-width: 360px;
		max-height: 677px;
		background: #2e363c7a;
		border: 1px solid #444;
		border-radius: 20px;
		padding: 30px 30px 50px 30px;
		transition: 0.2s;
	}

	.card-middle {
		background: linear-gradient(180deg, #fd4c00 0%, #f4753f 100%);
		border: 0.914765px solid rgba(255, 255, 255, 0.2);
		backdrop-filter: blur(11.8005px);
		border-radius: 23.7839px;
		padding: 30px 30px 50px 30px;
		transition: 0.2s;
	}

	.title-name h2 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 22px;
	}

	.row {
		margin-top: 30px;
		border: 0.5px solid #bdbdbd;
	}

	.row-top {
		max-width: 1480px;
		margin: 0 auto;
		margin-top: 138px;
		margin-bottom: 80px;
	}

	.price-and-month {
		display: flex;
		margin: 30px 0px 0px 0px;
		justify-content: space-around;
	}

	.price-and-month h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 70px;
	}

	.price-and-month h2 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 35px;
		color: var(--vermilion-600);
		margin-top: 5px;
	}

	.price-and-month-middle {
		display: flex;
		margin: 30px 0px 0px 0px;
		justify-content: space-around;
	}

	.price-and-month-middle h1 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 70px;
	}

	.price-and-month-middle h2 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 700;
		font-size: 35px;
		color: var(--white);
		margin-top: 5px;
	}

	.paragraph {
		max-width: 270px;
		padding: 0px 0px 0px 15px;
		margin-bottom: 40px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 14.5488px;
		color: #c9c9c9;
	}

	.paragraph-middle {
		max-width: 270px;
		padding: 0px 0px 0px 15px;
		margin-bottom: 40px;

		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 14.5488px;
		color: var(--white);
	}

	.more-infos {
		display: flex;
		flex-direction: column;
		margin-bottom: 40px;
	}

	.info {
		display: flex;
		margin-top: 20px;
	}

	.info h3 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 14.5488px;
		color: #bdbdbd;
		margin-left: 10px;
	}

	.info-middle {
		display: flex;
		margin-top: 20px;
	}

	.info-middle h3 {
		font-family: 'Inter';
		font-style: normal;
		font-weight: 400;
		font-size: 14.5488px;
		color: var(--white);
		margin-left: 10px;
	}

	.check {
		width: 23.28px;
		height: 18.19px;
	}

	.button {
		border: 2px solid #f4753f;
		padding: 15px 20px;
		color: var(--white);
		transition: 0.2s;
	}

	.button:hover {
		background: var(--vermilion-600);
	}

	.button-middle {
		padding: 15px 20px;
		box-sizing: border-box;
		background: #f4753f;
		border: 1.82953px solid #ffffff;
		transition: 0.2s;
	}

	.button-middle:hover {
		background: var(--white);
		color: var(--vermilion-600);
	}
</style>
