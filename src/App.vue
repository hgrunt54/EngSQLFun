<script setup lang="ts">
    import Banner from './components/Banner.vue'
    import Query from './components/Query.vue'
    import Expectation from './components/Expectation.vue'
    import User_Input from './components/User_Input.vue'
</script>

<template>
    <header>
        <Banner />
    </header>
    <Query class="query"/>
    <Expectation class="query"/>
    <User_Input class="query"/>
</template>

<style scoped>
    header {
        margin: 0 auto;
        text-align: center;
        border: 3px solid green;
        background-color: green;
    }
    .query {
        margin: 0 auto;
        padding: 1rem;
        text-align: center;
    }
</style>
