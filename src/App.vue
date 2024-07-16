<template>
    <div>
        <PageHeader />
        <MainHero />
        <PageFooter />
    </div>
    <!-- <RouterView /> -->
</template>

<script>

import PageHeader from '@/components/PageHeader.vue'
import MainHero from '@/components/MainHero.vue'
import PageFooter from '@/components/PageFooter.vue';

// import { RouterView } from 'vue-router'


export default {
    components: {
        PageHeader,
        MainHero,
        PageFooter
    }
}
</script>
