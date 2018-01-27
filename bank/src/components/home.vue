<template>
    <div class="home">
        <h1>Brief Bank</h1>
        <input type="text" v-model="message" placeholder="Search Terms"><br>
        <input type="text" v-model="message" placeholder="Date"></br>
        <button type="button">Search:</button>
    </div>
</template>

<script>
    export default {
        name: 'Home'
    }
</script>

<style scoped>

</style>