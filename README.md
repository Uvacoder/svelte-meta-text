# Svelte Meta Text

## Install

```bash
pnpm i -D svelte-meta-text
```

## Example

```html
<svelte:head>
	<title>Hello World</title>
	<Meta title='Hello World' description='Testing page of website' url='http://localhost:3000'></Meta>
</svelte:head>

<script lang="ts">
	import Meta from 'svelte-meta-text'
</script>

<h1>Hello World...</h1>
```