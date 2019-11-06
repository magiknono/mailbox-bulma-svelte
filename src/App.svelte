<script>
	import 'bulma/css/bulma.css'
	import { Button } from 'svelma'
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
	grid-template-columns:20vw 40vw 1fr;
	grid-template-rows:5em 1fr;
	grid-template-areas:
	"navuser navmenu navsearch"
	"navfilters listmail contentmail";
}
.navuser{
	grid-area: navuser;
}
.navmenu {
	grid-area: navmenu;
}
.navsearch {
	grid-area:navsearch;
}
.navfilters {
	grid-area:navfilters;
}
.listmail {
	grid-area:listmail;
}
.contentmail {
	grid-area:contentmail
}
/* understanding border with tailwind 
=====================================
border border-color

*/

	
</style>

<div class="mygrid">

	<nav class="navuser">Monica WHite</nav>
	<nav class="navmenu">
		<ul>
			<li><Button>mailbox</Button></li>
			<li>customers</li>
			<li>reporting</li>
			<li>manage</li>
		</ul>
	</nav>
	<nav class="navsearch">
		<input type="text" value="search">
	</nav>
	

	<nav class="navfilters">
			mailboxes
			<ul>
				<li>inbox</li>
				<li>flagged</li>
				<li>drafts</li>
				<li>assigned</li>
				<li>closed</li>
				<li>junk</li>
			</ul>
			folders
			<ul>
				<li>refunds</li>
				<li>discounts</li>
				<li>bugs</li>
			</ul>
	</nav>

	<div class="listmail">
		<section>
		from
		x days ago
		mail-start
		</section>
		<section>
		from
		x days ago
		mail-start
		</section>
		<section>
		from
		x days ago
		mail-start
		</section>
		<section>
		from
		x days ago
		mail-start
		</section>
		<section>
		from
		x days ago
		mail-start
		</section>
	</div>

	<div class="contentmail">
		<section>
		fix nav1
		fix title1
		content > with unders section
		</section>
		<section>
		fix nav1
		fix title1
		content > with unders section
		</section>
	</div>
	
</div>