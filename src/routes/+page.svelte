<script>
	import { goto } from '$app/navigation';
</script>

<div class="container mx-auto text-center">
	<h1 class="text-test text-huge">Tailwind vs. CSS</h1>
	<h2 class="text-2xl text-gray-800">
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
</div>
