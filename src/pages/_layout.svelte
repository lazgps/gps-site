<!-- routify:options preload="proximity" -->
<script>
    import Headr from './_components/Headr.svelte';
    import Nav from './_components/Nav.svelte';
    import Foot from './_components/Foot.svelte';
</script>

<div class="container bg-default h-screen min-h-screen mt-0 md:mx-20">
	<div class="sticky bg-white top-0 h-18 w-full my-6 py-6 z-50">
		<Headr />
		<Nav />
	</div>	
    <slot />
	<Foot />
</div>

