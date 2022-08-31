<script>
	import AsideLinks from '$lib/components/AsideLinks.svelte';
</script>

<main class="bg-gray-400 px-8 py-16">
	<section class="max-w-xl mb-16 text-slate-600">
		<article>
			<h2 class="text-5xl lowercase">hi, I'm sam 🐦</h2>
			<p class="text-2xl">
				some intro sentence that has the right kind of cutesy enthusiam about myself + my business
				;) lol
			</p>
		</article>
	</section>
	<section class="mb-8 grid grid-cols-3 gap-4 text-slate-600">
		<article>
			<h3 class="text-2xl font-bold mb-2 lowercase">another section with smaller info</h3>
			<p class="text-lg max-w-prose">
				this is the smaller info lorem ipsum bacon arcanum adeptus mechanicus
			</p>
		</article>
		<article>
			<h3 class="text-2xl font-bold mb-2 lowercase">another section with smaller info</h3>
			<p class="text-lg max-w-prose">
				this is the smaller info lorem ipsum bacon arcanum adeptus mechanicus
			</p>
		</article>
		<AsideLinks />
	</section>
</main>
