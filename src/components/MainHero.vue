<template>
    <section class="relative h-screen bg-cover bg-center" style="background-image: url('../assets/images/hero-background.jpg');">
        <div class="absolute inset-0 bg-black bg-opacity-80">
            <div class="relative z-1- flex flex-col justify-center items-center h-full text-center text-white">
                <p class="uppercase mt-4">
                    your hiking guide
                </p>
                <h1 class="text-5xl font-bold mb-5 capitalize">
                    be prepared for the mountains and beyond
                </h1>
                <a href="#content" class="mt-6 text-lg hover:underline capitalize animate-bounce">
                    scroll down
                </a>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'MainHero'
}

</script>