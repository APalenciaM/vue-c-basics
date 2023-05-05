<script>
export default {
    data() {
    return {
        name: 'Conditional',
        saw: false
        }
    }
}
</script>

<template>
    <div>
        <button v-on:click="saw = saw ? false : true">Show it!</button>
        <h1 v-if="saw">Hola</h1>
    </div>
</template>



<style scoped>

</style>