<script lang="ts">
    const { href = undefined, src, alt, username } = $props()
</script>

<div class="border border-solid border-gray-500 rounded-[1em] pt-1 pb-1 pl-2 pr-2">
    {#if href}
        <a rel="me" href={href} class="text-cyan-600 hover:underline">
            <div class="flex flex-row items-center gap-1 justify-center">
                <img class="w-[20px] h-[20px]" src="images/social/{src}" alt="{alt} logo"/>
                <p class="overflow-hidden">{username}</p>
            </div>
        </a>
    {:else}
        <div class="flex flex-row items-center gap-1 justify-center">
            <img class="w-[20px] h-[20px]" src="images/social/{src}" alt="{alt} logo"/>
            <p class="overflow-hidden">{username}</p>
        </div>
    {/if}
</div>