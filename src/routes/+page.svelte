<script lang="ts">
	import About from '@component/sections/about/About.svelte';
	import Feature from '@component/sections/feature/Feature.svelte';
	import Header from '@component/sections/header/Header.svelte';
	import Recommendation from '@component/sections/recommendation/Recommendation.svelte';
</script>

<Header />
<main>
	<About />
	<Feature />
	<Recommendation />
</main>

<svelte:head>
	<title>Oram | Furniture For Your Life</title>
</svelte:head>
