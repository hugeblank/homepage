<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<title>it's hugeblank</title>
	<meta name="description" content="the homepage">
		<!-- Facebook Meta Tags -->
	<meta property="og:url" content="https://hugeblank.dev"/>
	<meta property="og:type" content="website"/>
	<meta property="og:title" content="it's hugeblank"/>
	<meta property="og:description" content="the home page"/>
	<meta property="og:image" content="https://hugeblank.dev/images/hugeblank.png"/>

	<!-- Twitter Meta Tags -->
	<meta name="twitter:card" content="summary_large_image"/>
	<meta property="twitter:domain" content="hugeblank.dev"/>
	<meta property="twitter:url" content="https://hugeblank.dev"/>
	<meta name="twitter:title" content="it's hugeblank"/>
	<meta name="twitter:description" content="the home page"/>
	<meta name="twitter:image" content="https://hugeblank.dev/images/hugeblank.png"/>
</svelte:head>

<div class="min-w-7xl max-w-7xl pr-8 pl-8 ml-auto mr-auto">
	{@render children()}
	<footer class="text-center mt-24">hugeblank is a registered trademark of Hugeblank Entertainment. For more information please make a blood sacrifice to the harvest goddess Demeter.</footer>
</div>