<script>
    import Cta from "$lib/CTA.svelte"
    import Hero from "./Hero.svelte"

</script>

<Hero />

<a class="cta" href="/programme" >This week's programme</a>
<a class="cta" href="/personal" >Generate a programme</a>
<a class="cta" href="/discord" >Join the community</a>

<style >
    .cta {
        display: block;
        background-color: black;
        color: papayawhip;
        padding: 0.5rem 1rem;
    }
</style>