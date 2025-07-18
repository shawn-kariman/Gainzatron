<script>
    import Button from "$lib/components/ui/Button.svelte"
import Cta from "$lib/CTA.svelte"
    import Hero from "./Hero.svelte"

</script>

<Hero />
<Button href="/program" >This week's program</Button>
<Button href="/personal" >Generate a programme</Button>
<Button href="/discord" >Join the community</Button>

<style >
    .cta {
        display: block;
        background-color: black;
        color: papayawhip;
        padding: 0.5rem 1rem;
    }
</style>