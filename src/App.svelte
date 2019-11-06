<script>
	
</script>

<style>

/* mygrid
===========================
navuser navoptions navoptions == header
navfiters listmail contentmail == main
===========================
*/
.mygrid {
	display:grid;
	background-color:red;
	height:99vh;
	width:98vw;
}

/* understanding border with tailwind 
=====================================
border border-color

*/

	
</style>
<div class="mygrid">

<header>
	<nav class="navuser">Monica WHite</nav>
	<nav class="navoptions">
		<ul>
			<li>mailbox</li>
			<li>customers</li>
			<li>reporting</li>
			<li>manage</li>
		</ul>
		<input type="text" value="search">
	</nav>
</header>

<main>
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

	<article class="listmail">
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
	</article>

	<article class="contentmail">
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
	</article>
</main>

 </div>