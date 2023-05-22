<script>
	import Nav from "$lib/Nav.svelte";
	import "@unocss/reset/antfu.css";

	const routes = [{ display: "Lektion 1", link: "/01lektion1" }];
</script>

<Nav {routes} level={1}/>

<slot />

<style uno:preflights uno:safelist global></style>
