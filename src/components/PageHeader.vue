<template>
    <nav class="flex justify-between items-center p-4  bg-gray-800 text-white">
        <div class="text-2xl font-bold capitalize cursor-pointer">
            trailbliss
        </div>

        <ul class="flex space-x-6">
            <li class="capitalize hover:text-gray-400">
                <a href="/about">
                    about us
                </a>
            </li>
            <li class="capitalize hover:text-gray-400">
                <a href="/adventures">
                    adventures
                </a>
            </li>
            <li class="capitalize hover:text-gray-400">
                <a href="/contact">
                    contact us
                </a>
            </li>
        </ul>

        <div class="capitalize cursor-pointer hover:text-gray-400">
            account
        </div>
    </nav>
</template>

<script>
export default {
    name: 'PageHeader'
}

</script>