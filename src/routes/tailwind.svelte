<script>
	import Nav from "$lib/tailwind/Nav.svelte";
	import Hero from "$lib/tailwind/Hero.svelte";
	import Benefits from "$lib/tailwind/Benefits.svelte";
	import Features from "$lib/tailwind/Features.svelte";
</script>

<svelte:head>
	<script src="https://cdn.tailwindcss.com"></script>
	<script type="text/javascript" defer>
		tailwind.config = {
      theme: {
        extend: {
          colors: {
            'viko-black': '#17181c',
            'viko-grey': 'rgb(181, 181, 181)',
            'viko-maroon': '#830505',
            'viko-red': '#f95b5b',
            'viko-brown': '#242424'
          }
        }
      }
    }
	</script>
</svelte:head>

<Nav />

<section class="bg-viko-brown mt-16 mb-2 py-4">
	<div class="text-center text-viko-grey">
		<strong>Coming Soon!</strong> - Join the free
		<a class="has-text-weight-bold" href="/developers/">
			<span class="text-viko-red">early access programme</span>
		</a>
	</div>
</section>

<Hero />
<Benefits />
<Features />

<style>
	:global(body) {
		background-color: #17181c;
	}
</style>