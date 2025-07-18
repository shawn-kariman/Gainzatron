<script lang="ts" >
    import type { Snippet } from "svelte"

    type Props = {
        href: string,
        children: Snippet,
    }
    let { children, href } = $props();
</script>
<a 
    class="bg-orange-800 text-orange-100 px-4 py-2 rounded-xl"
    href={href}
>
    {@render children()}
</a>