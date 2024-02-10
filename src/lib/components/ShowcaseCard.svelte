<script lang=ts>
    export let backgroundColor: string = '';
	export let title: string = '';
    export let imageSrc: string;
</script>

<div class="{backgroundColor} w-full rounded-md flex justify-center my-4 flex-col p-10">
    {#if title != '' }
        <h1 class="lg:text-4xl md:text-3xl  text-white mb-10">
            {title}
        </h1>
    {/if}
    <img class="md:w-2/3 md:h-fit self-center rounded-md" alt="my-profile" src="{imageSrc}" />
</div>