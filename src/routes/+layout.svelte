<script>
	import favicon from '$lib/assets/favicon.svg';
	import '$lib/components/Footer.svelte';
	import '$lib/components/magnifier/Magnifier.svelte';
	let { children } = $props();
	export const ssr = false;
	export const prerender = true;
	export const trailingSlash = 'always';
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

<!--magnifier-->
<div style="max-width: 90%; margin-inline: auto">
	<csis-magnifier
		bg-image="https://res.cloudinary.com/csisideaslab/image/upload/v1759341280/dev-team/annie-spratt-4CKAvwj0nok-unsplash.jpg"
		background-image-alt="image alt"
		magnifier-zoom="2.5"
	></csis-magnifier>
</div>
<test-el text-color="#000" background-color="#eee"></test-el>

<style>
	:global(html, body) {
		height: 100vh;
	}
	:global(body) {
		display: grid;
		align-content: space-between;
		margin: 0;
	}
</style>
