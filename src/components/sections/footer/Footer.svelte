<script lang="ts">
	import { mail, map, phone } from '@component/logos/Icons.svelte';
	import { logo } from '@component/logos/Logos.svelte';
</script>

<footer class=" bg-primary text-white">
	<section class="links border-b border-[#265D5F]">
		<div class="py-10 px-6 lg:py-14 lg:pl-16 border-[#265D5F]">
			<h5 class="paragraph mb-5">Company</h5>
			<ul class="paragraph-sm grid gap-4 text-white/80 font-light">
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Blogs</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Linkedin</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Testimonials</a
					>
				</li>
			</ul>
		</div>

		<div class="py-10 px-6 lg:py-14 lg:pl-16 lg:border-l border-[#265D5F]">
			<h5 class="paragraph mb-5">Products</h5>
			<ul class="paragraph-sm grid gap-4 text-white/80 font-light">
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4">Home</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Category</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4">Cart</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Contact us</a
					>
				</li>
			</ul>
		</div>

		<div class="py-10 px-6 lg:py-14 lg:pl-16 lg:border-l border-[#265D5F]">
			<h5 class="paragraph mb-5">Managed Service</h5>
			<ul class="paragraph-sm grid gap-4 text-white/80 font-light">
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Privacy policy</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>What's included</a
					>
				</li>
				<li>
					<a href="/" class="transition hover:underline hover:text-white underline-offset-4"
						>Learn more</a
					>
				</li>
			</ul>
		</div>

		<div class="py-10 px-6 lg:py-14 lg:pl-16 lg:border-l border-[#265D5F]">
			<h5 class="paragraph mb-5">Get in touch</h5>
			<ul class="paragraph-sm grid gap-4 text-white/80 font-light">
				<li>
					<a href="/" class="inline-flex gap-3 items-center"
						><span>{@render phone()}</span> +880 1926457518</a
					>
				</li>
				<li>
					<a href="/" class="inline-flex gap-3 items-center"
						><span>{@render map()}</span> Mirpur 11, Dhaka, Bangladesh</a
					>
				</li>
				<li>
					<a href="/" class="inline-flex gap-3 items-center"
						><span>{@render mail()}</span> info@oram-furniture.com</a
					>
				</li>
			</ul>
		</div>
	</section>
	<section class="px-6 mt-12 lg:mt-24 pb-6">
		<div class="w-40 h-12 lg:w-[58rem] lg:h-[10rem] mx-auto">
			{@render logo('w-full h-full')}
		</div>
	</section>
</footer>

<style>
	.links {
		display: grid;
	}

	@media (min-width: 64rem) {
		.links {
			grid-template-columns: 4fr 4fr 4fr 5.25fr;
		}
	}

	@media (min-width: 96rem) {
		.links {
			grid-template-columns: repeat(4, 1fr);
		}
	}
</style>
