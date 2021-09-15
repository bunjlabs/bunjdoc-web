<script>
    import TreeSection from "./TreeSection.svelte";

    const sections = [{
        name: "Test 1",
        children: [
            {name: "subtest 1"},
            {name: "subtest 2"},
            {name: "subtest 3"},
        ]
    },
        {
        name: "Test 2",
        children: []
    }]
</script>

<div class="nav">
    {#each sections as value}
        <TreeSection value={value} />
    {/each}
</div>

<style>
    div.nav {
        background-color: #598392;
    }
</style>