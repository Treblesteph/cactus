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
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus11.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus12.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus13.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus14.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus15.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus16.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus17.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus18.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus19.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus20.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus21.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus22.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus23.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus24.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus25.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus26.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus27.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus28.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus29.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus30.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus31.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus32.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus33.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus34.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus35.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus36.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus37.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus38.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus39.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus40.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus41.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus42.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus43.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus44.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus45.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus46.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus47.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus48.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus49.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus50.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus51.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus52.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus53.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus54.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus55.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus56.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus57.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus58.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus59.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus60.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus61.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus62.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus63.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus64.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus65.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus66.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus67.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus68.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus69.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus70.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus71.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus72.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus73.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus74.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus75.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus76.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus77.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus78.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus79.png'
		},
		{
			src: 'https://raw.githubusercontent.com/Treblesteph/cactus/main/src/cactus80.png'
		}
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