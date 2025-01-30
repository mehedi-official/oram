<script lang="ts">
	import d from '$lib/assets/banner-section-bg.png';
</script>

<section
	class="grid gap-48 lg:gap-80 text-white bg-black-100 px-6 pt-36 lg:px-20 pb-20 bg-local lg:bg-fixed"
>
	<div class="flex">
		<h2 class="h3 lg:max-w-[30rem] uppercase font-normal">Make space for the things that matter</h2>
	</div>
	<div class="flex justify-end">
		<p class="paragraph-lg lg:max-w-[32rem] font-normal">
			Our furniture blends sustainable design with comfort and style, creating spaces that support
			what truly matters.
		</p>
	</div>
</section>

<style>
	section {
		background: linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)),
			url('$lib/assets/banner-section-bg.png');
		background-size: cover;
		background-repeat: no-repeat;
		background-position: center;
	}

	@media (min-width: 64rem) {
		section {
			background-attachment: fixed;
		}
	}
</style>
