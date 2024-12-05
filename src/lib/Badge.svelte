<script lang="ts">
    const { site, type = "gif", full = undefined, href = undefined, alt = undefined} = $props()
</script>

{#if full}
<a href="https://{href}"><img src="images/{site}.{type}" alt="{alt}" title="{alt}" style="margin-left: 8px;"></a>
{:else}
    <a href="https://{site}"><img src="images/{site}.{type}" alt="{site} badge" title="{site} badge" style="margin-left: 8px;"></a>
{/if}