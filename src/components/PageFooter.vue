<template>
    <footer class="bg-gray-900 text-white py-10">
        <div class="container mx-auto px-6">
            <div class="flex justify-between items-center">
                <div>
                    <span class="uppercase font-bold text-lg">
                        trailbliss
                    </span>
                    <p>
                        Get out there and discover your next slope, mountain and destination!
                    </p>
                    <p class="mt-4">
                        © 2024 Trailbliss, Inc. Terms &amp; Privacy
                    </p>
                </div>

                <div>
                    <ul>
                        <li class="capitalize flex items-center space-x-2">
                            <MapPinIcon class="w-5 h-5" />
                            <a href="#">
                                our adventures
                            </a>
                        </li>
                        <li class="capitalize flex items-center space-x-2">
                            <UserGroupIcon class="w-5 h-5" />
                            <a href="#">
                                join the club
                            </a>
                        </li>
                        <li class="capitalize flex items-center space-x-2">
                            <a href="#">
                                
                            </a>
                        </li>
                        <li class="capitalize flex items-center space-x-2">
                            <a href="#">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>


<script>
import { MapPinIcon, UserGroupIcon } from '@heroicons/vue/24/outline';


export default {
    name: 'PageFooter',
    components: {
        MapPinIcon,
        UserGroupIcon
    }
}

</script>

<!--

change the year dynamically

-->