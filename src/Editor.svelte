<script>

import TreeNavigation from "./tree/TreeNavigation.svelte";
</script>

<div class="editor">

    <TreeNavigation />

    <div class="content">
        123
    </div>
</div>

<style>

    div.editor {
        display: flex;
        flex-direction: row;
    }

    div.nav {

    }

    div.content {
        flex-grow: 1;
    }

</style>