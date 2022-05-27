<script>
    export let title;
    export let description;
    export let githubStars;
    export let url;
    export let icon;
    export const languages = [];
</script>

<div class="flex bg-gray-900 dark:bg-gray-100 shadow-md rounded-md w-96 m-4 p-4">
    <div class="bg-gray-100 dark:bg-gray-900 p-2 rounded-md">
        <img class="w-24 h-auto object-contain rounded" src={icon}/>
    </div>
    <div class="ml-4">
        <p class="text-gray-100 dark:text-gray-900 text-lg font-semibold">{title}</p>
    </div>
</div>