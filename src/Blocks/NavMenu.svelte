<script>
    import UserSearch from "../Components/UserSearch.svelte"
</script>

<style>
.navmenu {
	grid-area: navmenu;
    padding:1.75em;
}
</style>

<nav class="level navmenu has-background-grey-light">
    <div class="level-left">
        <div class="level-item">
            <div class="buttons">
                <button class="button is-dark">mailbox</button>
                <button class="button is-dark">customers</button>
                <button class="button is-dark">report</button>
                <button class="button is-dark">manage</button>
            </div>
        </div>
    
    </div>

    <div class="level-right">
        <div class="level-item">
            <UserSearch/>
        </div>
    </div>
   
</nav>
