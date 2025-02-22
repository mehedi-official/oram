<script>
	import { logo } from '@component/logos/Logos.svelte';
</script>

<nav class=" hidden uppercase lg:grid grid-cols-2 py-5 px-10">
	<div>
		<ul class="flex gap-3">
			<li>
				<a
					href="/"
					class="paragraph-sm py-2 px-3.5 transition hover:bg-white/10 border border-white rounded-full"
					>Cart</a
				>
			</li>
			<li>
				<a
					href="/"
					class="paragraph-sm py-2 px-3.5 transition hover:bg-white/10 border border-white rounded-full"
					>Categories</a
				>
			</li>
			<li>
				<a
					href="/"
					class="paragraph-sm py-2 px-3.5 transition hover:bg-white/10 border border-white rounded-full"
					>Home</a
				>
			</li>
		</ul>
	</div>

	<section class="flex justify-between">
		<a href="/" class=" -translate-x-1/2">
			{@render logo()}
		</a>
		<div>
			<a
				href="/"
				class="paragraph-sm font-medium py-2 px-3.5 transition hover:opacity-90 bg-teal-200 text-black-100 rounded-full"
				>Sign up</a
			>
		</div>
	</section>
</nav>

<nav class="uppercase py-8 px-6 lg:hidden">
	<section class="flex justify-between items-center">
		<div>
			{@render logo()}
		</div>
		<div>
			<a
				href="/"
				class="paragraph-sm font-medium py-2 px-3.5 bg-teal-200 text-black-100 rounded-full"
				>Sign up</a
			>
		</div>
	</section>
</nav>
