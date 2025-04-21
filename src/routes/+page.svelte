<script>
	import AllBlocksES from '$comps/AllBlocksES.svelte';
	import meta_img from '$lib/images/meta__img__en.jpg';

	const title = 'Cómo utilizar sistemas para extraer beneficios de los mercados';
	const desc =
		'FORMACIÓN SIN COSTE PARA TRADERS ASPIRANTES - ¡Por qué el Método Sistemático es realmente su mejor apuesta para ganar dinero en los mercados!';
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={desc} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={desc} />
	<meta property="og:image" content={meta_img} />
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={desc} />
	<meta name="twitter:image" content={meta_img} />
</svelte:head>

<AllBlocksES />
