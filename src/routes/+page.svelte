<script>
	import Header from './Header.svelte';
	import SectionOne from './SectionOne.svelte';
	import SectionTwo from './SectionTwo.svelte';
	import SectionThree from './SectionThree.svelte';
	import SectionFour from './SectionFour.svelte';
	import SectionFive from './SectionFive.svelte';
	import SectionSix from './SectionSix.svelte';
	import SectionSeven from './SectionSeven.svelte';
	import './style.css';
</script>

<header>
	<Header />
</header>

<main>
	<SectionOne />
	<SectionTwo />
	<SectionThree />
	<SectionFour />
	<SectionFive />
	<SectionSix />
	<SectionSeven />
</main>

<style>
	:root {
		--shark-950: #1d2429;
		--vermilion-600: #fd4c00;
		--white: #fff;
	}
</style>
