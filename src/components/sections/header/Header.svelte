<script lang="ts">
	import Navbar from "./Navbar.svelte";
</script>

<header class="text-white h-dvh bg-black relative">
    <Navbar />
    <section class="grid gap-1 mt-36">
        <h1 class="text-6xl text-center lg:text-[8rem] leading-base font-medium">Embrace Minimalism</h1>
        <p class="h5 text-center w-4/5 mx-auto lg:mx-0 lg:w-full lg:text-right lg:pr-24">Design Your Home Simply and Purposefully</p>
    </section>
        
    <section class="absolute bottom-12 right-1/2 translate-x-1/2 w-4/5 text-center lg:text-left lg:translate-x-0 lg:max-w-lg lg:right-20">
        <div></div>
        <p class="paragraph">Our minimalist furniture features clean lines and functionality, enhancing any space with timeless, clutter-free pieces that create a calm, sophisticated atmosphere.</p>
    </section>
</header>

<style>
    header {
        background: linear-gradient(-122.211deg, rgba(19, 50, 53, 30%) 18%, rgba(19, 50, 53, 0%) 100%), url("$lib/assets/banner_img.avif");
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        background-attachment: fixed;
    }
</style>