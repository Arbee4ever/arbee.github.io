<script lang="ts">
	import "$lib/css/global.scss";
	import "$lib/css/normalize.css";
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<svelte:head>
	<meta charset="utf-8" />
	<meta name="description"
				content="I (ARBEE) am a german guy who likes programming fun things. I'm creating Minecraft mods and Websites with Svelte.">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="canonical" href="https://arbeeco.de">
	<meta name="twitter:site" content="@ARBEE_codes" />
	<meta name="twitter:creator" content="@ARBEE_codes" />
	<meta property="og:url" content="https://arbeeco.de" />
	<meta name="theme-color" content="#2b8eaf" />
	<meta name="keywords" content="Blog, Modding, Gamedev, Arbee, GitHub">

	<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
	<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
	<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
	<link rel="manifest" href="/site.webmanifest">
	<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
	<meta name="msapplication-TileColor" content="#da532c">
	<meta name="theme-color" content="#2B8EAF">
</svelte:head>

<Header></Header>
<slot></slot>
<Footer></Footer>