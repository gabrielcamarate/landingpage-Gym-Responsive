<script>
    import Header from "./Header.svelte"; 
    import SectionOne from "./SectionOne.svelte"; 
    import SectionTwo from "./SectionTwo.svelte"; 

    import "./style.css";
</script>

<header>
    <Header/>
</header>

<main>
    <SectionOne/>
    <SectionTwo/>
</main>


<style>
    :root{
        --shark-950: #1D2429;
        --vermilion-600: #fd4c00;
        --white: #fff;
    }
</style>