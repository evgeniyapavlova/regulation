<script>
	import AllBlocks from '$comps/AllBlocks.svelte';
	// import meta_img from '$lib/images/meta__img__en.jpg';

	const title = 'IQ Option';
	const desc =
		'IQOPTION EUROPE LTD is authorized and operated under the Cyprus Securities and Exchange Commission (CySEC) with license number 247/14 and is permitted to offer services only to residents of the EEA in accordance with CySEC regulations.';
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={desc} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={desc} />
	<!-- <meta property="og:image" content={meta_img} /> -->
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content={title} />
	<meta name="twitter:description" content={desc} />
	<!-- <meta name="twitter:image" content={meta_img} /> -->
</svelte:head>

<AllBlocks />
