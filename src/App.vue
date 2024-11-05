<script setup>
    import Header from "./components/header.vue"
    import Intro from './components/intro.vue'
    import Service from './components/service.vue'
    import Examples from './components/examples.vue'
    import Faqs from './components/faqs.vue'
    import Footer from './components/footer.vue'
</script>

<template>
    <Header/>
    <main>
        <Intro/>
        <Service/>
        <Examples/>
        <Faqs/>
    </main>
    <Footer/>
</template>

<style lang="scss" scoped>

</style>
