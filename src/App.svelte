<script>
	
</script>

<style>

/* flexbox
===========================
navuser navoptions navoptions == header
navfiters listmail contentmail == main
===========================
*/
.container {
	display:grid;
	background-color:red;
}

/* understanding border with tailwind 
=====================================
border border-color

*/

	
</style>
<div class="container border border-black">

<header>
	<nav class="navuser border border-blue-300">Monica WHite</nav>
	<nav class="navoptions border border-blue-500">
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
	<nav class="navfilters border border-indigo-500">
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

	<article class="listmail border border-green-500">
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

	<article class="contentmail border border-yellow-500">
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