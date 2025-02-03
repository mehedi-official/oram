<script>
	import about_banner from '$lib/assets/about_us_banner.png?enhanced';
	import { arrow_top_angle } from '@component/logos/Icons.svelte';
</script>

<section class="pt-[4.5rem] pb-12 px-6 lg:px-20">
	<div class="flex gap-4 justify-between flex-col lg:gap-0 lg:flex-row mb-10">
		<h2 class="h3 leading-base text-black-200">We Are ORAM</h2>
		<p class="paragraph-lg text-black-300 lg:max-w-[65%]">
			At ORAM, we create furniture that embodies our values just like our name, Organic, Resilient,
			Artistic, Modern (ORAM). Inspired by nature and crafted with eco-friendly materials, our
			pieces are built to last and designed to blend artistry with sleek, contemporary style. ORAM
			stands for sustainable elegance, where beauty meets responsibility.
		</p>
	</div>

	<section class="grid gap-7">
		<div>
			<enhanced:img src={about_banner} alt="" class="rounded-2xl"> </enhanced:img>
		</div>

		<div class="grid gap-5 lg:max-w-[80%]">
			<p class="paragraph-lg text-black-300">
				Choosing ORAM means investing in quality craftsmanship that lasts for generations. Our
				nature-inspired designs bring comfort, style, and purpose to your space, while our
				commitment to sustainability reduces environmental impact. With ORAM, you’re not just
				furnishing your home—you’re making a conscious choice for a better future.
			</p>
			<a
				href="/"
				class="inline-flex items-center gap-2 paragraph transition-all hover:underline underline-offset-4 text-black-100"
				>Read more about us <span>{@render arrow_top_angle('w-3 h-3', '#121212')}</span></a
			>
		</div>
	</section>
</section>
