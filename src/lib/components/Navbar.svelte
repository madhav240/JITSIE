<script>
	let isOpen = true;
</script>

<nav>
	<div class="lg:hidden">
		<a href="/">
			<img class=" h-32 ml-4 -mt-1 fixed object-contain" src="/logo.png" alt="" />
		</a>
		<div class="fixed inline-block right-8 top-8">
			<button class="relative" on:click={() => (isOpen = !isOpen)}>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="w-8 h-8 {isOpen ? 'hidden' : 'block '}"
					viewBox="0,0,256,256"
				>
					<g
						fill="none"
						fill-rule="nonzero"
						stroke="#ffffff"
						stroke-width="2"
						stroke-linecap="butt"
						stroke-linejoin="miter"
						stroke-miterlimit="10"
						stroke-dasharray=""
						stroke-dashoffset="0"
						font-family="none"
						font-weight="none"
						font-size="none"
						text-anchor="none"
						style="mix-blend-mode: normal"
						><g transform="scale(10.66667,10.66667)"
							><path d="M2,12h20" /><path d="M2,6h20" /><path d="M2,18h20" /><path
								d="M2,12h20"
							/><path d="M22,12h-20" /></g
						></g
					>
				</svg>
				<svg
					fill="#ffffff"
					class="w-8 h-6 {isOpen ? 'block' : 'hidden'}"
					version="1.1"
					id="Capa_1"
					xmlns="http://www.w3.org/2000/svg"
					xmlns:xlink="http://www.w3.org/1999/xlink"
					viewBox="0 0 94.926 94.926"
					xml:space="preserve"
					stroke="#ffffff"
					><g id="SVGRepo_bgCarrier" stroke-width="0" /><g
						id="SVGRepo_tracerCarrier"
						stroke-linecap="round"
						stroke-linejoin="round"
					/><g id="SVGRepo_iconCarrier">
						<g>
							<path
								d="M55.931,47.463L94.306,9.09c0.826-0.827,0.826-2.167,0-2.994L88.833,0.62C88.436,0.224,87.896,0,87.335,0 c-0.562,0-1.101,0.224-1.498,0.62L47.463,38.994L9.089,0.62c-0.795-0.795-2.202-0.794-2.995,0L0.622,6.096 c-0.827,0.827-0.827,2.167,0,2.994l38.374,38.373L0.622,85.836c-0.827,0.827-0.827,2.167,0,2.994l5.473,5.476 c0.397,0.396,0.936,0.62,1.498,0.62s1.1-0.224,1.497-0.62l38.374-38.374l38.374,38.374c0.397,0.396,0.937,0.62,1.498,0.62 s1.101-0.224,1.498-0.62l5.473-5.476c0.826-0.827,0.826-2.167,0-2.994L55.931,47.463z"
							/>
						</g>
					</g></svg
				>
			</button>
			{#if isOpen}
				<div
					class="absolute right-0 z-20 w-44 py-2 mt-2 origin-top-right bg-neutral-800 rounded-md shadow-xl dark:bg-gray-800"
				>
					<a
						href="#"
						class="block px-6 py-3 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						blogs
					</a>
					<a
						href="#"
						class="block px-6 py-3 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						team
					</a>
					<a
						href="#"
						class="block px-6 py-3 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						Contact
					</a>
					<a
						href="#"
						class="block px-6 py-3 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						About
					</a>
					<a
						href="#"
						class="block px-6 py-3 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						Events
					</a>
					<a
						href="#"
						class="block px-6 py-3 border-t border-neutral-700 text-sm text-white uppercase transition-colors duration-300 transform"
					>
						Join
					</a>
				</div>
			{/if}
		</div>
	</div>
	<div class="hidden lg:block">
		<div class="w-full flex">
			<a href="/">
				<img class=" h-36 ml-12 fixed -mt-2 object-contain" src="/logo.png" alt="" />
			</a>
			<div class="flex flex-row gap-x-14 w-fit mx-auto mt-12">
				<a href="" class="text-white uppercase hover:underline"> Blogs </a>
				<a href="" class="text-white uppercase hover:underline"> team </a>
				<a href="" class=" text-white uppercase hover:underline"> Contact </a>
				<a href="" class="text-white uppercase hover:underline"> About </a>
				<a href="" class="text-white uppercase hover:underline"> Events </a>
			</div>

			<div class="mt-12 mr-16 fixed right-2">
				<a href="" class=" text-white rounded-md bg-neutral-800 py-2.5 px-7 uppercase"> Join </a>
			</div>
		</div>
	</div>
</nav>
