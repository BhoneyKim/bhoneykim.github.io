<script>
	export let name;
	// import Splash from './Splash.svelte';
	import Contents from './Contents.svelte';
	
</script>


<Contents/>



<style>
	:global(body){
		padding: 0;
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #000000;
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
