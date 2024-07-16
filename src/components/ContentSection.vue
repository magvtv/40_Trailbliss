<template>
    <section class="py-16">
        <div class="container mx-auto flex flex-wrap">
            <div class="w-full md:w-1/2 p-5">
                <h2 class="text-3xl font-bold mb-5">
                    {{ title }}
                </h2>
                <p class="text-lg mb-5">
                    {{ details }}
                </p>
                <a href="" class="capitalize text-blue-500 hover:underline">
                    read more
                </a>
            </div>

            <div class="w-full md:w-1/2 p-5">
                <img :src="image" :alt="altText">
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'ContentSection',
    props: {
        title: String,
        details: String,
        image: String,
        altText: String
    }
}

</script>