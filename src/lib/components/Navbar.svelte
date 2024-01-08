<script>
	import { onMount } from 'svelte';

	onMount(() => {
		document.getElementById('toggleBtn').addEventListener('click', function () {
			document.getElementById('navList').classList.toggle('hidden');
		});
	});
</script>

<nav class="bg-black p-2 mt-0 w-full border-2 border-gray-400">
	<div class="container mx-auto flex flex-wrap items-center justify-between">
		<div class="flex items-center">
			<a class="text-white no-underline hover:text-white hover:no-underline" href="/">
				<img src="/img/image-6@2x.png" class="h-20 md:h-16 w-auto px-2" alt="Website Logo" />
			</a>
		</div>
		<div class="md:flex items-center space-x-4 justify-end">
			<button id="toggleBtn" class="md:hidden text-white"> Menu </button>
			<ul
				class="list-reset flex flex-col md:flex-row md:flex-none items-end md:items-center hidden md:flex"
				id="navList"
			>
				<li class="mr-3">
					<a class="inline-block py-2 px-4 text-white no-underline bg-black shadow-lg" href="#"
						>Home</a
					>
				</li>
				<li class="mr-3">
					<a class="inline-block py-2 px-4 text-white no-underline bg-black shadow-lg" href="#"
						>Events</a
					>
				</li>
				<li class="mr-3">
					<a class="inline-block py-2 px-4 text-white no-underline bg-black shadow-lg" href="/blogs"
						>Blogs</a
					>
				</li>
				<li class="mr-3">
					<a class="inline-block py-2 px-4 text-white no-underline bg-black shadow-lg" href="/team"
						>Team</a
					>
				</li>
				<li class="mr-3">
					<a class="inline-block py-2 px-4 text-white no-underline bg-black shadow-lg" href="#"
						>Contact</a
					>
				</li>
				<li class="ml-4 md:ml-6 mt-4 md:mt-0">
					<a
						class="inline-block py-2 px-4 text-black no-underline bg-purple-200 rounded-full"
						href="#">Join Us</a
					>
				</li>
			</ul>
		</div>
	</div>
</nav>
