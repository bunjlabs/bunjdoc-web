<script>
import Fa from 'svelte-fa'
import { faUserCircle } from '@fortawesome/free-solid-svg-icons'
</script>

<div class="header">
    <div class="logo">
        Bunjdoc
    </div>
    <div class="profile">
        <Fa icon={faUserCircle} />
    </div>
</div>

<style>
    div.header {
        display: flex;
        flex-direction: row;
        align-items: center;

		width: 100%;

        padding: 4px 8px;
        color: #ffffff;
        background-color: #1C1D21;
    }

    div.logo {
        flex-grow: 1;
    }

    div.profile {
        font-size:24px;
    }
</style>