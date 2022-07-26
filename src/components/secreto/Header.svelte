<script>
	import { fly } from 'svelte/transition';
</script>

<svelte:head>
	<title>secreto</title>
</svelte:head>

<section>
	<div class="text-center mx-auto">
		<h1 class="font-inter font-black tracking-wide uppercase text-white text-4xl">
			<span class="animate-pulse" transition:fly={{ y: 500, duration: 10000 }}>✨</span> secreto
		</h1>
	</div>
</section>
