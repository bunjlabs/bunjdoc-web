<script>
    import TreeSection from "./TreeSection.svelte";

    export let value

    let {name, children} = value;
</script>

<div class="section">
    <div class="name">{name}</div>
    {#if children}
        <div class="children">
            {#each children as value}
                <TreeSection value={value}/>
            {/each}
        </div>
    {/if}
</div>

<style>
    div.children {
        margin-left: 8px;
    }

    div.name:hover {
        cursor: pointer;

        background-color: #00000010;
    }
</style>