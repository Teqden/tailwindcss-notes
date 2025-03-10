<nav class="fixed top-0 flex w-full items-center justify-between bg-gray-800 p-3 text-white">
	<span>Tailwind Nav</span>
	<div class="flex gap-4">
		<a href="#" class="hover:text-gray-300">Home</a>
		<a href="#" class="hover:text-gray-300">About</a>
		<a href="#" class="hover:text-gray-300">Contact</a>
	</div>
</nav>

<nav class="nav-settings">
	<span>CSS Nav</span>
	<div class="nav-items">
		<a href="#" class="nav-link">Home</a>
		<a href="#" class="nav-link">About</a>
		<a href="#" class="nav-link">Contact</a>
	</div>
</nav>

<style>
	.nav-settings {
		position: fixed; /* fixed . it ensures the nav bar stay in the same place when user scroll the page*/
		top: 60px; /* it should be 0 but i used 60 to avoid hided by the tailwind nav . it points out the distance between nav and the top of screen*/
		display: flex; /* flex */
		width: 100%; /* w-full */
		align-items: center; /* items-center . it makes the items centered in vertical way*/
		justify-content: space-between; /* justify-between */
		background-color: #1f2937; /* bg-gray-800 */
		padding: 12px; /* p-3 */
		color: white; /* text-white */
	}

	.nav-items {
		display: flex; /* flex */
		gap: 16px; /* gap-4 */
	}

	.nav-link {
		color: white; /* text-white */
		text-decoration: none;
	}

	.nav-link:hover {
		color: #d1d5db; /* hover:text-gray-300 */
	}
</style>
