<script>
    import ProjectCard from "$lib/components/ProjectCard.svelte";

    const projects = [
        {
            title: "Discordlist.gg",
            icon: "/dlist.png",
        },
        {
            title: "LNX Search",
            icon: "/lnx.png",
        },
        {
            title: "Lust",
            icon: "/lust.png",
        },
        {
            title: "ReWrk",
            icon: "/rewrk.png",
        }
    ]
</script>

<div class="w-3/4 py-8">
    <h3 class="text-center">My Projects</h3>
    <div class="flex flex-wrap items-center justify-evenly p-4">
        {#each projects as proj}
            <ProjectCard {...proj}/>
        {/each}
    </div>
</div>