<script>
	import Nav from "$lib/tailwind/Nav.svelte";
	import Hero from "$lib/tailwind/Hero.svelte";
	import Benefits from "$lib/tailwind/Benefits.svelte";
	import Features from "$lib/tailwind/Features.svelte";
</script>

<svelte:head>
	<script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<Nav />

<section class="has-background-light my-2 py-4">
	<div class="has-text-centered has-text-grey-dark">
		<strong>Coming Soon!</strong> - Join the free
		<a class="has-text-weight-bold" href="/developers/"
			>early access programme</a
		>
	</div>
</section>

<Hero />
<Benefits />
<Features />
