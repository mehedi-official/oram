<script lang="ts">
	import feature_1 from '$lib/assets/feature_1.png?enhanced';
	import feature_2 from '$lib/assets/feature_2.png?enhanced';
	import { arrow_top_angle } from '@component/logos/Icons.svelte';
</script>

<section class="text-white">
	<section class="grid grid-cols-1 lg:grid-cols-2">
		<div class="bg-[#784C42] py-24 px-6 lg:px-32 grid gap-12">
			<div class="grid gap-4">
				<h3 class="h4 uppercase">Eco-Friendly Innovation</h3>
				<p class="paragraph-lg text-white/80">
					We prioritize sustainable innovation by using renewable materials and environmentally
					conscious production methods. ORAM’s designs embody a commitment to reducing environmental
					impact while delivering sophisticated, high-quality furniture.
				</p>
			</div>
			<a
				href="/"
				class="inline-flex gap-2 items-center paragraph text-teal-300 transition-all underline lg:no-underline hover:underline underline-offset-4"
				>Read more about us <span>{@render arrow_top_angle('w-3 h-3')}</span></a
			>
		</div>
		<div>
			<enhanced:img src={feature_1} class="w-full h-full object-cover" alt="Feature 1" />
		</div>
	</section>

	<section class="grid grid-cols-1 lg:grid-cols-2">
		<div class="order-last lg:order-first">
			<enhanced:img src={feature_2} class="w-full h-full object-cover" alt="Feature 2" />
		</div>
		<div class="bg-[#784C42] py-24 px-6 lg:px-32 grid gap-12">
			<div class="grid gap-4">
				<h3 class="h4 uppercase">Timeless Durability</h3>
				<p class="paragraph-lg text-white/80">
					At ORAM, every piece of furniture is thoughtfully crafted using eco-friendly and
					responsibly sourced materials. Our commitment to sustainability ensures that each design
					not only enhances your space but also supports a healthier planet.
				</p>
			</div>
			<a
				href="/"
				class="inline-flex gap-2 items-center paragraph text-teal-300 transition-all underline lg:no-underline hover:underline underline-offset-4"
				>Read more about us <span>{@render arrow_top_angle('w-3 h-3')}</span></a
			>
		</div>
	</section>
</section>
