<script lang="ts">
	import About from '@component/sections/about/About.svelte';
	import Banner from '@component/sections/banner/Banner.svelte';
	import Feature from '@component/sections/feature/Feature.svelte';
	import Footer from '@component/sections/footer/Footer.svelte';
	import Header from '@component/sections/header/Header.svelte';
	import Recommendation from '@component/sections/recommendation/Recommendation.svelte';
</script>

<Header />
<main>
	<About />
	<Feature />
	<Recommendation />
	<Banner />
</main>
<Footer />

<svelte:head>
	<title>Oram | Furniture For Your Life</title>
</svelte:head>
