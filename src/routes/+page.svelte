<script>
	import AllBlocksPT from '$comps/AllBlocksPT.svelte';
	import meta_img from '$lib/images/meta__img__en.jpg';

	const title = 'Como Usar Sistemas para Extrair Lucros dos Mercados';
	const desc =
		'TREINAMENTO SEM CUSTO PARA ASPIRANTES A TRADERS - Por que o Método Sistêmico é, na verdade, sua melhor opção para ganhar dinheiro nos mercados!';
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

<AllBlocksPT />
