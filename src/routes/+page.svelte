<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Hero from "$lib/components/Hero.svelte";
    import Statement from "$lib/components/Statement.svelte";
    import TechnologyShowcase from "$lib/components/TechnologyShowcase.svelte";
    import CurrentLabPlatform from "$lib/components/CurrentLabPlatform.svelte";
    import ProgressCarousel from "$lib/components/ProgressCarousel.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    <Hero />
    <Statement />
    <TechnologyShowcase />
    <CurrentLabPlatform />
    <ProgressCarousel />
</main>

