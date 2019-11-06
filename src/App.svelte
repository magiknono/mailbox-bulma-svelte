<script>
	import "bulma/css/bulma.css"

	import NavUser from "./Blocks/NavUser.svelte"
	import NavMenu from "./Blocks/NavMenu.svelte"
	import NavFilters from "./Blocks/NavFilters.svelte"
	import ListMail from "./Blocks/ListMail.svelte"
	import ContentMail from "./Blocks/ContentMail.svelte"
</script>

<style>

/* mygrid
===========================
navuser navoptions navoptions == header
navfiters listmail contentmail == main
===========================
*/
body {
	overflow-y:hidden;
	width:100vw;
}
.mygrid {
	display:grid;
	border:10px solid #eee;
	height:100vh;
	grid-template-columns:minmax(15vw,190px) 25vw 1fr;
	grid-template-rows:3.5em 1fr;
	grid-row-gap:2.5em;
	grid-template-areas:
	"navuser navmenu navmenu"
	"navfilters listmail contentmail";
}
	
</style>

<div class="mygrid">

<NavUser />	

<NavMenu />


<NavFilters />

<ListMail />

<ContentMail />
	
</div>