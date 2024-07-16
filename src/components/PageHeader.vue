<template>
    <header class="flex text-white justify-between items-center p-3">
        <div class="text-xl font-bold capitalize cursor-pointer">
            trailbliss
        </div>
        <nav class="flex space-x-6 items-center">
            <a href="/about" class="flex items-center space-x-2">
                <InformationCircleIcon class="w-5 h-5" />
                <span class="capitalize">
                    about
                </span>
            </a>
           <a href="/guides" class="flex items-center space-x-2">
                <MapIcon class="w-5 h-5" />
                <span class="capitalize">
                    guides
                </span>
            </a>
            <a href="/adventures" class="flex items-center space-x-2">
                <MapPinIcon class="w-5 h-5" />
                <span class="capitalize">
                    adventures
                </span>
            </a>
        </nav>
        <div>
            <a href="" class="capitalize flex items-center justify-center space-x-1 cursor-pointer">
                <UserIcon class="w-5 h-5" />
                <span>
                    account
                </span>
            </a>
        </div>
    </header>
</template>

<script>

import { InformationCircleIcon, MapIcon, MapPinIcon, UserIcon} from '@heroicons/vue/24/outline'


export default {
    name: 'PageHeader',
    components: {
        InformationCircleIcon,
        MapIcon,
        MapPinIcon,
        UserIcon
    }
}

</script>

<style scoped>
header {
  background: rgba(0, 0, 0, 0.5);
}
</style>