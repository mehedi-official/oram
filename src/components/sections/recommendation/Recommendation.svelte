<script lang="ts">
	import recommendation_1 from '$lib/assets/recommendation_1.png?enhanced';
	import recommendation_2 from '$lib/assets/recommendation_2.png?enhanced';
	import recommendation_3 from '$lib/assets/recommendation_3.png?enhanced';
	import { arrow_top_angle } from '@component/logos/Icons.svelte';
</script>

<section class=" py-16">
	<div class="hidden lg:flex justify-between px-16">
		<div class="rounded-lg translate-y-28 overflow-hidden max-w-[19.5rem] h-[21.625rem]">
			<enhanced:img src={recommendation_1} alt="recommendation 1" />
		</div>
		<div class="rounded-lg overflow-hidden max-w-[19.5rem] h-[21.625rem]">
			<enhanced:img src={recommendation_2} alt="recommendation 2" />
		</div>
	</div>

	<section class="px-6 lg:px-0 lg:max-w-[60%] ml-auto grid gap-10">
		<div class="grid gap-10">
			<h2 class="h3 text-black-100">Products that <br /> We Highly Recommend</h2>
			<div class="w-fit relative">
				<div class="rounded-lg overflow-hidden max-w-[19.5rem] h-[21.625rem]">
					<enhanced:img src={recommendation_3} alt="recommendation 3" />
				</div>
				<a
					href="/"
					class="absolute right-0 top-0 translate-x-1/5 lg:translate-x-1/2 -translate-y-1/2 border-4 border-white bg-teal-100 inline-flex items-center justify-center w-16 h-16 rounded-full text-white"
					>{@render arrow_top_angle('w-4 h-4')}</a
				>
			</div>
		</div>

		<div class="grid gap-8 max-w-2xl">
			<div class="grid gap-4">
				<h2 class="h5 lg:text-4xl text-black-100">
					Explore our most recommended pieces, blending modern design with sustainable
					craftsmanship. Each item is thoughtfully made to bring lasting style and function to your
					space.
				</h2>
				<p class="paragraph lg:paragraph-lg text-black-300 max-w-lg">
					Our furniture combines the natural beauty of premium wood with the comfort of soft,
					sustainable materials. Each piece is expertly crafted to balance durability and elegance,
					offering timeless designs that bring warmth and comfort to any space.
				</p>
			</div>

			<a href="/" class="paragraph text-black-100">Read more about us</a>
		</div>
	</section>
</section>
