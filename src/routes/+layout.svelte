<script lang="ts">
	import favicon from '$lib/assets/favicon.png';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}



<main>
    <!--<img src={fp} alt="A robot working in a futuristic environment" /> 

    <div class="wrapper nav">
      <div class="nav-left">
        <div class="logo">
			<a href="#"><img src="/images/sonK02g1HhQpYMD96kBANE5hEYY.png" alt="Robotspace Logo" ></a>
		</div>
       
      </div>
      <nav class="nav-links">
        <a href="#products" class="nav-primary">Products</a>
        <a href="#about">About</a>
		
        <a href="#careers">we're hiring</a>
		
        <div class="nav-cta">
          <a href="#demo" class="btn btn-accent">Book a demo</a>
        </div>
      </nav>
      <button class="mobile-menu">☰</button>
    </div>

-->
</main>