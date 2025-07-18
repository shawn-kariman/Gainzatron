<script>
    import Button from "$lib/components/ui/Button.svelte"

</script>
<div class="stack h-[50svh] bg-gradient-to-br from-orange-500 via-orange-700 to-teal-500">
    <div class="background"></div>
    <div class="flex flex-col items-center place-self-center">
        <h1 class="place-self-center sm:text-5xl md:text-6xl lg:text-7xl bg-gradient-to-br from-orange-500 via-orange-700 to-teal-500 bg-clip-text text-transparent">Gainzatron</h1>
        <Button href="/contact" >Contact</Button>
    </div>
</div>

<style lang="postcss">
    .background{
        margin: 1rem;
        border-radius: 1rem;
        background: linear-gradient( 90deg, #202020, #282828);
    }
</style>