<template>
	<div class="bg-blue-800 text-blue-100 w-64 space-y-6 px-2 py-6">
		<!-- header -->
		<a href="" class="text-white flex items-center space-x-2 px-4">
			<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
				/>
			</svg>
			<span>VUE 3 </span>
		</a>
		<!-- body -->
		<nav>
			<a href="#" class="block py-2 px-4 rounded transition duration-200 hover:bg-blue-700 hover:text-white">Home</a>
			<a href="/about" class="block py-2 px-4 rounded transition duration-200 hover:bg-blue-700 hover:text-white"
				>About</a
			>
			<a href="/detail" class="block py-2 px-4 rounded transition duration-200 hover:bg-blue-700 hover:text-white"
				>Detail</a
			>
			<a href="/pages" class="block py-2 px-4 rounded transition duration-200 hover:bg-blue-700 hover:text-white"
				>Pages</a
			>
		</nav>
		<!-- footer -->
	</div>
</template>

<script>
export default {
	setup() {
		return {}
	},
}
</script>
