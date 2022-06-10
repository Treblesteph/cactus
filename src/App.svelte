<script>
	export let name;

	import { Images } from "svelte-images";
	const images = [
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus1.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus2.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus3.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus4.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus5.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus6.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus7.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus8.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus9.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus10.png'
		}
		// {
		// 	src: "/cactus11.png"
		// },
		// {
		// 	src: "/cactus12.png"
		// },
		// {
		// 	src: "/cactus13.png"
		// },
		// {
		// 	src: "/cactus14.png"
		// },
		// {
		// 	src: "/cactus15.png"
		// },
		// {
		// 	src: "/cactus16.png"
		// },
		// {
		// 	src: "/cactus17.png"
		// },
		// {
		// 	src: "/cactus18.png"
		// },
		// {
		// 	src: "/cactus19.png"
		// },
		// {
		// 	src: "/cactus20.png"
		// },
		// {
		// 	src: "/cactus21.png"
		// },
		// {
		// 	src: "/cactus22.png"
		// },
		// {
		// 	src: "/cactus23.png"
		// },
		// {
		// 	src: "/cactus24.png"
		// },
		// {
		// 	src: "/cactus25.png"
		// },
		// {
		// 	src: "/cactus26.png"
		// },
		// {
		// 	src: "/cactus27.png"
		// },
		// {
		// 	src: "/cactus28.png"
		// },
		// {
		// 	src: "/cactus29.png"
		// },
		// {
		// 	src: "/cactus30.png"
		// },
		// {
		// 	src: "/cactus31.png"
		// },
		// {
		// 	src: "/cactus32.png"
		// },
		// {
		// 	src: "/cactus33.png"
		// },
		// {
		// 	src: "/cactus34.png"
		// },
		// {
		// 	src: "/cactus35.png"
		// },
		// {
		// 	src: "/cactus36.png"
		// },
		// {
		// 	src: "/cactus37.png"
		// },
		// {
		// 	src: "/cactus38.png"
		// },
		// {
		// 	src: "/cactus39.png"
		// },
		// {
		// 	src: "/cactus40.png"
		// },
		// {
		// 	src: "/cactus41.png"
		// },
		// {
		// 	src: "/cactus42.png"
		// },
		// {
		// 	src: "/cactus43.png"
		// },
		// {
		// 	src: "/cactus44.png"
		// },
		// {
		// 	src: "/cactus45.png"
		// },
		// {
		// 	src: "/cactus46.png"
		// },
		// {
		// 	src: "/cactus47.png"
		// },
		// {
		// 	src: "/cactus48.png"
		// },
		// {
		// 	src: "/cactus49.png"
		// },
		// {
		// 	src: "/cactus50.png"
		// },
		// {
		// 	src: "/cactus51.png"
		// },
		// {
		// 	src: "/cactus52.png"
		// },
		// {
		// 	src: "/cactus53.png"
		// },
		// {
		// 	src: "/cactus54.png"
		// },
		// {
		// 	src: "/cactus55.png"
		// },
		// {
		// 	src: "/cactus56.png"
		// },
		// {
		// 	src: "/cactus57.png"
		// },
		// {
		// 	src: "/cactus58.png"
		// },
		// {
		// 	src: "/cactus59.png"
		// },
		// {
		// 	src: "/cactus60.png"
		// },
		// {
		// 	src: "/cactus61.png"
		// },
		// {
		// 	src: "/cactus62.png"
		// },
		// {
		// 	src: "/cactus63.png"
		// },
		// {
		// 	src: "/cactus64.png"
		// },
		// {
		// 	src: "/cactus65.png"
		// },
		// {
		// 	src: "/cactus66.png"
		// },
		// {
		// 	src: "/cactus67.png"
		// },
		// {
		// 	src: "/cactus68.png"
		// },
		// {
		// 	src: "/cactus69.png"
		// },
		// {
		// 	src: "/cactus70.png"
		// },
		// {
		// 	src: "/cactus71.png"
		// },
		// {
		// 	src: "/cactus72.png"
		// },
		// {
		// 	src: "/cactus73.png"
		// },
		// {
		// 	src: "/cactus74.png"
		// },
		// {
		// 	src: "/cactus75.png"
		// },
		// {
		// 	src: "/cactus76.png"
		// },
		// {
		// 	src: "/cactus77.png"
		// },
		// {
		// 	src: "/cactus78.png"
		// },
		// {
		// 	src: "/cactus79.png"
		// },
		// {
		// 	src: "/cactus80.png"
		// },
		// {
		// 	src: "/cactus81.png"
		// },
		// {
		// 	src: "/cactus82.png"
		// },
		// {
		// 	src: "/cactus83.png"
		// },
		// {
		// 	src: "/cactus84.png"
		// },
		// {
		// 	src: "/cactus85.png"
		// },
		// {
		// 	src: "/cactus86.png"
		// },
		// {
		// 	src: "/cactus87.png"
		// },
		// {
		// 	src: "/cactus88.png"
		// },
		// {
		// 	src: "/cactus89.png"
		// },
		// {
		// 	src: "/cactus90.png"
		// },
		// {
		// 	src: "/cactus91.png"
		// },
		// {
		// 	src: "/cactus92.png"
		// },
		// {
		// 	src: "/cactus93.png"
		// },
		// {
		// 	src: "/cactus94.png"
		// },
		// {
		// 	src: "/cactus95.png"
		// },
		// {
		// 	src: "/cactus96.png"
		// },
		// {
		// 	src: "/cactus97.png"
		// },
		// {
		// 	src: "/cactus98.png"
		// },
		// {
		// 	src: "/cactus99.png"
		// },
		// {
		// 	src: "/cactus100.png"
		// },
	];
</script>

<main>
	<img id='title' src='https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus0.png'/>
	<h1>A cactus 🌵 100 ways</h1>
	<!-- <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->

	<Images {images} gutter={5} />
</main>

<style>
	main {
		height: 75vh;
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	#title {
		width: 30%;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>