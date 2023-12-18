<script>
    /** @type {import('./$types').LayoutData} */
    import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	import { page } from '$app/stores';
    export let data;
</script>

<div class="app">
	{#if $page.url.pathname==='/user/login/views/admin'}
		<!-- do not include header if logged into admin portal -->
	{:else}
		<Header /> 
	{/if}
	<main>
		<slot />
	</main>
	{#if $page.url.pathname==='/user/login/views/admin'}
		<!-- do not include footer if logged into admin portal -->
	{:else}
 	   <Footer />
	{/if}

	<!-- <footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer> -->
</div>