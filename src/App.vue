<template>
    <div>
        <PageHeader />
        <MainHero />
        <ContentSection />
        <PageFooter />
    </div>
    <!-- <RouterView /> -->
</template>

<script>

import PageHeader from '@/components/PageHeader.vue'
import MainHero from '@/components/MainHero.vue'
import PageFooter from '@/components/PageFooter.vue';
import ContentSection from './components/ContentSection.vue';

// import { RouterView } from 'vue-router'


export default {
    components: {
        PageHeader,
        MainHero,
        ContentSection,
        PageFooter
    }
}
</script>
