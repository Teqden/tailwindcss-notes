<div class="container mx-auto flex flex-col items-center">
	<button class="mt-10 block rounded bg-blue-500 px-4 py-2 text-white hover:bg-blue-700"
		>Tailwind Button</button
	>
	<button class="button-settings hover-transition">CSS Button</button>
</div>

<style>
	.button-settings {
		margin-top: 40px; /* equals to mt-10 */
		display: block; /* equals to block */
		background-color: #3b82f6; /* equals to bg-blue-500 */
		padding: 8px 16px; /* equals to px-4 and py-2 */
        color: white; /* equals to text-white */
		border-radius: 0.25rem; /* make a rounded corner */
		font-size: 1rem; /* set the same default font size with Tailwind */
		text-align: center; /* make the text center */
	}
	.hover-transition {
		transition: background-color 0.2s ease-in-out;
	}
	@media (hover: hover) {
		.hover-transition:hover {
			background-color: #1d4ed8;
		}
	}
</style>
