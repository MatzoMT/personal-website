<script>
	export let name;
	import Experience from './Experience.svelte';
	import NavBar from './NavBar.svelte';
	let src="./meiniceland.png";
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Questrial&display=swap" rel="stylesheet">
</svelte:head>

	<NavBar /> 
<section class="w-full h-screen">
	<img
	  src="images/meiniceland.jpeg"
	  class="object-cover w-full h-full"
	  alt="Image alt text"
	/> 

</section>
<h1>Playing with svelte</h1>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
	html, 
body {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    overflow-x: hidden; 
	font-family: 'Questrial';
}
  </style>