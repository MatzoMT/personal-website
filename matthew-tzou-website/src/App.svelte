<script>
	export let name;
	import Experience from './Experience.svelte';
	let src="./meiniceland.png";
</script>


<section class="w-full h-screen">
	<img
	  src="images/meiniceland.jpeg"
	  class="object-cover w-full h-full"
	  alt="Image alt text"
	/> 
  </section>

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
}
  </style>