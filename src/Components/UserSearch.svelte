<script>
    let query = "";
    let search;
    let data;
    let results=[];
    let visible = false;
    search = async function search() {
            let data = [];
            const response = await fetch("https://randomuser.me/api/");
            const json = await response.json();
            data = json.results[0];
            visible= true;
            results= [data]
            
            
    }

</script>

<style>
.search {
    margin-top:0.5em;
}
</style>

<div class="field is-grouped">
    <div class="control">
        <ul>
            <li> <input bind:value={query} on:keyup={search} class="input is-dark search" type="text" placeholder="search contacts"></li>
            <li>
            {#if visible}
            <img src={results[0].picture.thumbnail} alt="#" style="position:fixed;"/><input type="select" style="position:fixed;" value={results[0].login.username}>
            {/if}
            </li>
        </ul>
       
         
    </div>
   
</div>
