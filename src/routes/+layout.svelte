<script lang="ts">
    import type { Snippet } from 'svelte';
    import type { LayoutData } from './$types';
    import '@fontsource-variable/inter';
    import "../app.css";

    let { data, children }: { data: LayoutData, children: Snippet } = $props();
</script>

{@render children()}

<style>
    :global(body) {
        font-family: 'Inter Variable', sans-serif;
    }
</style>