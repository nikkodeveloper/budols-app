<script lang="ts">
	import '../app.pcss';
	import 'iconify-icon';
	import Header from "$lib/sections/header.svelte"
</script>


<div class="page-wrap bg-hero-pattern min-h-screen">
	<Header />
	<main>
		<div class="main-wrap relative w-full px-6 py-12 bg-white shadow-xl shadow-slate-700/10 ring-1 ring-gray-900/5 md:max-w-3xl md:mx-auto lg:max-w-4xl lg:pt-16 lg:pb-28">
			<slot />
		</div>
	</main>
	<footer>
	  
	</footer>
</div>