<script>
	import { goto } from '$app/navigation';
</script>

<div class="container mx-auto text-center">
	<h1 class="text-test text-huge">Tailwind vs. CSS</h1>
	<h2 class="mt-5 text-2xl text-gray-800">
		Example 1 -> 
		<a
			class="underline"
			href="/button"
			on:click={(e) => {
				e.preventDefault();
				goto('/button');
			}}
		>
			'Button'
		</a>
	</h2>
    <h2 class="mt-5 text-2xl text-gray-800">
		Example 2 -> 
		<a
			class="underline"
			href="/navbar"
			on:click={(e) => {
				e.preventDefault();
				goto('/navbar');
			}}
		>
			'Navigation Bar'
		</a>
	</h2>
</div>
