<script>
	import { fly } from 'svelte/transition';

	async function getBooks() {
		let response = await fetch('https://raw.githubusercontent.com/yuxxeun/nxd/main/data/libs.json');
		let books = await response.json();
		return books;
	}
	const promise = getBooks();
</script>

<div class="text-center justify-center items-center mx-auto">
	{#await promise}
		<div class="my-3">
			<img
				src="/loading.svg"
				class="animate-spin-slow mx-auto my-10"
				alt="Reactivity...."
				width="200"
			/>
		</div>
	{:then book}
		{#each book as book}
			<ul
				class="my-4 py-4 backdrop-blur-md bg-white rounded-lg"
				transition:fly={{ y: 150, duration: 1500 }}
			>
				<li class="text-xl text-black space-x-2 font-space px-5">
					<span class="font-extrabold text-fuchsia-500">{book.judul}</span>
					— {book.penulis}
					<span class="text-center font-semibold bg-fuchsia-500 text-white px-2 rounded-md"
						>{book.status}</span
					>
					<span class="text-fuchsia-500 bg-white font-bold px-2 rounded-md">{book.tahun}</span>
				</li>
			</ul>
		{/each}
	{:catch error}
		<div class="my-10">
			<img src="/loading.svg" class="animate-spin mx-auto my-10" alt="Reactivity..." width="200" />
			<p class="text-pink-600 font-space italic text-2xl">
				Look like there's something wrong with you. <br /> ehm wait... it's not with you, it's my mini-server
				i guess.
			</p>
		</div>
	{/await}
</div>
