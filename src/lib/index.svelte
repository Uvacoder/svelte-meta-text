<script lang="ts">
	export let title: string
	export let description: string
	export let url: string
</script>

<meta name="description" content={description} />
<link rel="canonical" href={url} />
<meta property="og:locale" content="id_ID" />
<meta property="og:type" content="article" />
<meta property="og:title" content={title} />
<meta property="og:description" content={description} />
<meta property="og:url" content={url} />
<meta property="og:image" content="https://cdn.statically.io/og/{encodeURIComponent(title)}.jpg" />
<meta property="og:image:width" content="2048" />
<meta property="og:image:height" content="1170" />
<meta name="twitter:card" content="summary_large_image" />