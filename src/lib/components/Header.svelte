<script>
	const openShopTab = () => {
		window.open('https://www.etsy.com/uk/shop/NightingaleKnitsGB', '_blank');
	};
</script>

<header class="text-white bg-[url('/header-bg.jpg')]" style="background-size: cover">
	<div class="px-8 py-16 bg-gradient-to-r from-black">
		<div class="max-w-lg grid grid-cols-1 gap-8">
			<h2 class="text-xl font-bold lowercase">uniquely crafted hand-dyed yarn</h2>
			<h1 class="text-6xl font-bold">Nightingale Knits</h1>
			<p class="text-lg lowercase">Est. 2020 | Sam nightingale🐦 | indie yarn dyer</p>
			<nav>
				<button
					class="btn btn-lg bg-gradient-to-r from-red-500 to-rose-500 text-lg lowercase"
					on:click={openShopTab}
				>
					<img
						src="https://img.icons8.com/fluency-systems-filled/48/000000/shopping-bag-full.png"
						alt="shopping bag icon"
					/> Visit my shop
				</button>
			</nav>
		</div>
	</div>
</header>
