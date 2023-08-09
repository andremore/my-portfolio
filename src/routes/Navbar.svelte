<script>
	import logo from '$lib/images/logo.svg';
</script>

<header class="grid grid-cols-3 items-center my-4">
	<section class="flex items-center">
		<div>
			<a href="/">
				<img src={logo} alt="Logo" />
			</a>
		</div>
		<h1 class="ml-4 text-2xl">andremore</h1>
	</section>

	<section class="flex justify-between text-xl col-start-3 col-end-4">
		<nav>
			<ul class="flex justify-center">
				<li>
					<a href="/">home</a>
				</li>
				<li class="mx-5">
					<a href="/">work</a>
				</li>
				<li>
					<a href="/">contact me</a>
				</li>
			</ul>
		</nav>

		<div class="flex">socials</div>
	</section>
</header>

<style>
</style>
