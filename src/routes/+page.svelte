<script lang="ts">
    import ShowcaseCard from '$lib/components/ShowcaseCard.svelte';

</script>

<div class="relative isolate px-6 pt-5 lg:px-8 col-auto">
    <div class="primary-color lg:h-2/6  w-full bg-primary inline-grid lg:grid-cols-2 md:grid-cols-1 gap-4 lg:divide-x-4 p-5 rounded-md">
        <div class="flex flex-col space-y-4 justify-center lg:px-20">
            <h1 class="text-5xl">
                JR PARREÑO
            </h1>
            <h1 class="text-3xl">
                | Software Engineer
            </h1>
            <p class="text-gray-700 md:text-2xl text-justify">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
                incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation 
                ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
        </div>

        <div class="flex justify-center">
            <img class="md:w-2/4 md:h-fit self-center rounded-md" alt="my-profile" src="/profile.jpg" />
        </div>
    </div>
    <div id="demoApps" class="w-full my-5">
        <h1 class="text-5xl divide-y-4 divide-blue-200">
            Demo Apps
        </h1>
        <hr class="w-full h-1 bg-gray-100 my-2 rounded">
    </div>
    <ShowcaseCard 
        title="Nike Demo 🔥"
        backgroundColor="bg-black"
        imageSrc='/nike-mockup.png'
    />
    <ShowcaseCard 
        title="IMDB 🍿 with RapidApi Integration"
        backgroundColor="bg-black"
        imageSrc='/imdb-mockup.png'
    />
</div>