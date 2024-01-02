<script context="module" lang="ts">
	export const prerender = true;
</script>

<svelte:head>
	<title>HELLO :)</title>
	<meta name="description" content="Jon Highsmith's personal website." />
	<!-- why did i make this a svelte app and not just a static html page? the world may never know... -->
</svelte:head>

<section>
	<h1>Hi there, I'm Jon. <img class="stamp" src="/hell-yes.gif" alt="A man's hand giving a big thumbs up."></h1>
	<h2>
		I'm a <b>web developer</b> from Atlanta 
		<img class="stamp" src="/peach.gif" alt="A delicious peach.">, 
		home of the chicken wing <img class="stamp" src="/lemon-pepper.gif" alt="A delicious chicken wing.">. I currently work at 
		<a 
			href="https://orion.com"
			target="_blank"
			>
			Orion Advisor Solutions</a>.
		<img class="stamp" src="/bullish.gif" alt="A red arrow flying upward, resembling a financial performance chart.">
	</h2>
	<h2><b><a target="_blank" href="/jon-highsmith-resume-summer-2022.pdf">Download my resume here.</a></b></h2>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		align-items: flex-start;
	}

	h1 {
		width: 100%;
	}
</style>
