<script lang="ts">
	import '../app.css';
	import type { Snippet } from 'svelte';

	type Props = {
		children: Snippet<[]>;
	};

	let props: Props = $props();
</script>

{@render props.children?.()}
