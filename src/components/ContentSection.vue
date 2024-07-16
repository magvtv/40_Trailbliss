<template>
    <section id="content" class="bg-gray-900 py-20 text-white">
        <div class="container mx-auto px-5">
            <div class="grid md:grid-cols-2 gap-12">
                <div v-for="(section, index) in sections" :key="index" class="flex flex-col items-center">
                    <img :src="section.image" alt="" class="w-full h-64 object-cover mb-5">
                    <h2 class="text-2xl font-bold">
                        {{ section.title }}
                    </h2>
                    <p class="mt-4">
                        {{ section.details }}
                    </p>
                    <a href="#" class="mt-5 text-lg underline">
                        Read more
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'ContentSection',
    data() {
        return {
            sections: [
                {
                    image: '',
                    title: 'What Level of Hiker are You',
                    details: 'Determining what level of hiker you are can be an important tool when planning future hikes',
                },
                {
                    image: '',
                    title: 'Picking The Right Hiking Gear',
                    details: 'The nice thing about beginning a hiking experience is that you do not really need a gear',
                },
                {
                    image: '',
                    title: 'Understand your Map & Timing',
                    details: 'To start, print out the hiking guide and the map. If it is raining, throw them in a zip-lock bag',
                }
            ]
        }
    }
}

</script>