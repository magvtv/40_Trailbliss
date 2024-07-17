<template>
	<section id="content" class="bg-gray-900 py-20 text-white">
		<div class="container mx-auto px-5">
			<div class="grid md:grid-cols-3 gap-12">
				<div v-for="(section, index) in sections" :key="index"
					class="flex flex-col justify-center items-center cursor-pointer p-5">
					<img :src="section.image" alt=""
						class="md:w-full rounded-3xl border-none opacity-75 hover:opacity-100 object-cover mb-2 filter grayscale transform hover:scale-105 hover:grayscale-0 transition-all duration-500">
					<h2 class="text-2xl my-2 font-bold text-center cursor-pointer">
						{{ section.title }}
					</h2>
					<p class="my-2 text-center">
						{{ section.details }}
					</p>
					<a href="#" class="mt-5 text-sm underline text-yellow-500 hover:text-yellow-600">
						read more
					</a>
					<div class="">
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>

import hiking2 from '@/assets/images/hiking-2.jpg'
import hiking4 from '@/assets/images/hiking-4.jpg'
import hiking5 from '@/assets/images/hiking-5.jpg'



export default {
	name: 'ContentSection',
	data() {
		return {
			sections: [
				{
					image: hiking2,
					title: 'What level of hiker could you be?',
					details: 'Determining what level of hiker you are can be an important tool when planning future hikes',
				},
				{
					image: hiking4,
					title: 'Picking The Right Hiking Gear',
					details: 'The nice thing about beginning a hiking experience is that you do not really need a gear',
				},
				{
					image: hiking5,
					title: 'Understand your Map & Timing',
					details: 'To start, print out the hiking guide and the map. If it is raining, throw them in a zip-lock bag',
				},
				{
					image: hiking2,
					title: 'What Level of Hiker are You',
					details: 'Determining what level of hiker you are can be an important tool when planning future hikes',
				},
				{
					image: hiking4,
					title: 'Picking The Right Hiking Gear',
					details: 'The nice thing about beginning a hiking experience is that you do not really need a gear',
				},
				{
					image: hiking5,
					title: 'Understand your Map & Timing',
					details: 'To start, print out the hiking guide and the map. If it is raining, throw them in a zip-lock bag',
				}
			]
		}
	}
}

</script>