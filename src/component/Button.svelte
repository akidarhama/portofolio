<script>
    let animation = false;
    export let text;
    export let action
</script>

<button class=" bg-transparent border-2 border-[#22A39F] py-2 px-3 rounded-md transition hover:shadow-md hover:shadow-[#22A39F] text-black dark:text-white"
        on:click={action}
>
    {text}
</button>