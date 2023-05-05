<script>
export default {
    data() {
        return {
            sum: "2 + 2"
        }
    },
    computed: {
        ShowSum(){
            return this.sum;
        }
    }
}
</script>

<template>
    <div>
        <h1>{{ShowSum}}</h1>
    </div>
</template>



<style scoped>

</style>