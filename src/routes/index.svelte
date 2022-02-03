<script>
    
    let title = "Saubhagya's Website";

    let titleNew = () => {
        title = "Apoorv's Website";
    };
</script>


<div>
    <h1 class="text-3xl font-bold underline text-fuchsia-900">Welcome to {title}</h1>
    <p>Saubhagya is a good boy</p>
    <p>
        Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
    </p>
    <button on:click={titleNew}>Change title</button>
    <input class="border-2" type="text" bind:value={title} />
</div>

<style>
    div {
        text-align: center;
    }
</style>
