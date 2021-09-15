<script>
import Header from "./Header.svelte";

import Editor from "./Editor.svelte";

</script>

<main>
	<Header />
	<Editor />
</main>

<style>
	main {
		width: 100vw;
	}

	:global(*, body, html) {
		margin: 0;
		padding: 0;

		box-sizing: border-box;

		--black: #000000ff;
		--oxford-blue: #14213dff;
		--orange-web: #fca311ff;
		--platinum: #e5e5e5ff;
		--white: #ffffffff;
	}

</style>