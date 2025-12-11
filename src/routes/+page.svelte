

<script>
    import Nav from '$lib/comp/nav.svelte';
    import Hero from '$lib/comp/hero.svelte';  
    import Tcom from '$lib/comp/tcom.svelte';     
    import Gal from '$lib/comp/gal.svelte';  
    import Team from '$lib/comp/team.svelte';
    import Pro from '$lib/comp/pro.svelte';
    import Products from '$lib/comp/products.svelte';
    import About from '$lib/comp/about.svelte';


</script>


<main>

    <Nav />

    <Hero />

    <!--companies logo-->
    <Tcom />

    <!-- Vision / About -->
  <About />

    <!-- Products -->
    <Products />

    <!-- Process -->
    <Pro />
        

    <!-- Team -->
   <Team />

    <!-- Careers -->
	<Gal />

</main>
